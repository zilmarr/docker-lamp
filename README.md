# docker-lamp
Ambiente LAMP completo usando Docker.

### O que está disponível no ambiente?
* Servidor apache2 com PHP
* PHPMyAdmin
* MySQL 5.7

### Requisitos:
* O ambiente foi criado utilizando:

> Docker version 18.09.6, build 481bc77

> docker-compose version 1.24.0-rc1, build 0f3d4dda

### Como utilizar esse projeto?
* Clone o repositório
> git clone https://github.com/zilmarr/docker-lamp.git
* Entre na pasta do projeto e inicie o ambiente com o docker-compose
```
cd docker-lamp/
docker-compose up -d
```
* Após esse comando serão criadas duas pastas:
  * **webdata**: seus arquivos html, php, etc. deverão ser colocados aqui.
  * **dbdata**: a persistência do seu banco será feita aqui. Não é necessário alterar nada.
* Acesse seu projeto através do endereço http://localhost
* A gerência do seu PHPMyAdmin estará disponível em http://localhost:8080

#### Valores padrão
* Usuário do banco: lamp
* Senha do banco: lamp
* Nome do banco: lamp
