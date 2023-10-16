# JavaContatosWeb

**JavaContatosWeb** é um aplicativo web de gerenciamento de contatos desenvolvido em Spring MVC com PostgreSQL como banco de dados. Este projeto permite que você crie, leia, atualize e delete informações de contato.

## Pré-requisitos

Antes de começar, certifique-se de ter instalado o seguinte:

- Java Development Kit (JDK)
- Apache Maven
- PostgreSQL
- Um servidor de aplicativos compatível com Spring, como Tomcat

## Configuração do Banco de Dados

1. Crie um banco de dados PostgreSQL com o nome `contatos`.
2. Atualize as informações de conexão com o banco de dados no arquivo `src/main/resources/application.properties`.

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/contatos
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
