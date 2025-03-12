# API CRUD com Spring Boot

Este é um projeto de estudo focado na implementação de uma API REST com operações CRUD (Create, Read, Update, Delete) utilizando Spring Boot e PostgreSQL.

## 🛠 Tecnologias Utilizadas

- Java 23
- Spring Boot 3.4.3
- PostgreSQL
- Flyway para migração de banco de dados
- Spring Data JPA
- Maven
- Postman (para testes de API)

## 📋 Pré-requisitos

- Java 23
- Maven
- PostgreSQL
- Postman (para testes)

## 🚀 Configuração do Projeto

1. Clone o repositório:
```bash
git clone https://github.com/victorhugoguimaraes/spring-boot-crud-api.git
```

2. Configure o banco de dados PostgreSQL no arquivo `application.properties`

3. Execute o projeto:
```bash
mvn spring-boot:run
```

## 📚 Documentação da API

A API oferece endpoints para operações CRUD básicas. Você pode encontrar uma coleção do Postman com todos os endpoints na pasta `postman`.

### Endpoints Principais:

- `GET /api/projects` - Lista todos os recursos
- `GET /api/projects/{id}` - Obtém um recurso específico
- `POST /api/projects` - Cria um novo recurso
- `PUT /api/projects/{id}` - Atualiza um recurso existente
- `DELETE /api/projects/{id}` - Remove um recurso

## 🔧 Configuração do Banco de Dados

O projeto utiliza Flyway para gerenciamento de migrações do banco de dados. As migrações podem ser encontradas em `src/main/resources/db/migration`.

## 🧪 Testes

Para executar os testes:
```bash
mvn test
```

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## ✨ Autor

Victor Guimarães

---
⌨️ com ❤️ por [Victor Guimarães]  
