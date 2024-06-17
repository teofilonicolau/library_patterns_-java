# Descrição do Desafio

Neste projeto, foi desenvolvida uma solução prática que explora o conceito de Padrões de Projeto. O objetivo era criar uma aplicação que gerenciasse uma biblioteca de livros, utilizando tecnologias modernas e boas práticas de desenvolvimento.

## Projeto

O projeto consiste em uma aplicação de gerenciamento de biblioteca, onde é possível listar, adicionar, atualizar e excluir livros. O projeto foi desenvolvido usando o framework Spring Boot, que facilita o desenvolvimento de aplicativos Java.

![image](https://github.com/teofilonicolau/library_patterns_-java/assets/97030160/c39b72ea-ed9c-47db-bed9-37ba52a3bb01)

## Tecnologias Utilizadas

- Spring Boot: Framework Java para criar aplicativos de forma rápida e fácil.
- H2 Database: Banco de dados em memória para armazenar os dados da aplicação durante o desenvolvimento.
- Swagger: Ferramenta para documentar e testar APIs de forma interativa.
- Springdoc: Biblioteca que automatiza a geração de documentação de API usando Spring Boot.

## Utilização do Springdoc

Para integrar o Swagger na aplicação, foi utilizado o Springdoc. Esta biblioteca simplifica a geração de documentação da API, permitindo que os desenvolvedores visualizem e testem os endpoints de forma interativa.

Para mais informações sobre o Springdoc, visite [springdoc.org](https://springdoc.org/).

## Usando o Projeto

### Acesso ao Console H2

Primeiro, você precisa acessar o console do H2 para inserir alguns dados manualmente.
- Você pode acessar o console H2 no navegador usando o seguinte URL: http://localhost:8080/h2-console.
![image](https://github.com/teofilonicolau/library_patterns_-java/assets/97030160/8523c816-342e-460c-a44d-4e2ab1dc836e)

No campo "JDBC URL", você deve usar o mesmo URL que configurou no arquivo application.properties, que é jdbc:h2:mem:testdb.

### Acesso ao Banco de Dados

Depois de acessar o console H2, você deve ser capaz de ver uma interface para acessar o banco de dados.
- Você pode usar SQL para interagir com o banco de dados.

### Inserindo Dados

Você pode inserir alguns dados manualmente no banco de dados usando instruções SQL.

```sql
INSERT INTO Book (title, author) VALUES ('Aventuras de Sherlock Holmes', 'Arthur Conan Doyle');
INSERT INTO Book (title, author) VALUES ('O Senhor dos Anéis', 'J.R.R. Tolkien');
INSERT INTO Book (title, author) VALUES ('Orgulho e Preconceito', 'Jane Austen');
INSERT INTO Book (title, author) VALUES ('1984', 'George Orwell');
INSERT INTO Book (title, author) VALUES ('Cem Anos de Solidão', 'Gabriel García Márquez');
```

### Verificando os Dados

Depois de inserir os dados, você pode verificar se foram inseridos corretamente executando uma instrução SELECT para recuperar os dados que você inseriu.
- ![image](https://github.com/teofilonicolau/library_patterns_-java/assets/97030160/b19c1cb5-3430-41cb-ad70-86719fbfb8e4)

### Acessar o Swagger UI

- Vá para o Swagger UI usando o seguinte URL: http://localhost:8080/swagger-ui.html.
- Localize os Endpoints CRUD de Livros.
- ![image](https://github.com/teofilonicolau/library_patterns_-java/assets/97030160/c9974814-ed28-4c01-ab9c-2c882a0ab703)
