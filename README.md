# Pitzi Ruby Challenge Backend API

Desenvolvimento de uma API para realização de registo de assinaturas.

## Como rodar

O serviço está totalmente configurado para ser utilizado através de um servidor [Heroku](https://pitzi-api.herokuapp.com) e um [SPA](https://github.com/monoxchd/pitzi-user-registrations) desacoplado que funciona como frontend.

### Iniciar independente do Heroku

A API utiliza Postgresql como banco de dados, portanto, após clonar o projeto, seguir os seguintes passos para iniciá-lo.

```
bundle install 
```

```
sudo service postgresql start 
```

```
rake db:create
```

```
rake db:migrate
```

```
rails s
```

### Testes

Foram realizados testes de Modelos e Requests através da ferramenta RSpec. Após seguir os passos para iniciar o sistema individualmente. é só digitar no bash

```
Rspec
```
