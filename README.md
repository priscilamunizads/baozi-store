# Baozi Store API 🥟

API REST desenvolvida em Spring Boot e MySQL para gestão de clientes, produtos e pedidos da loja Baozi Store.

## 🚀 Tecnologias Utilizadas
- Java 17
- Spring Boot
- Spring Data JPA
- MySQL
- Maven
- Postman

## 📌 Endpoints Principais

### Clientes (`/clientes`)
- `GET /clientes` - Lista todos os clientes
- `GET /clientes/{id}` - Busca cliente por ID
- `POST /clientes` - Cadastra um novo cliente
- `DELETE /clientes/{id}` - Remove um cliente

### Produtos (`/produtos`)
- `GET /produtos` - Lista todos os produtos
- `GET /produtos/{id}` - Busca produto por ID
- `POST /produtos` - Cadastra um novo produto
- `DELETE /produtos/{id}` - Remove um produto

### Pedidos (`/pedidos`)
- `GET /pedidos` - Lista todos os pedidos
- `GET /pedidos/{id}` - Busca pedido por ID
- `POST /pedidos` - Cadastra um novo pedido
- `DELETE /pedidos/{id}` - Remove um pedido