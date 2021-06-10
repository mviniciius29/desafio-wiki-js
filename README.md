# Desafio Wiki.js

Desafio de instalação do Wiki.js utilizando containers.

### 📋 Pré-requisitos

* Docker Desktop

### 🔧 Instalação

O projeto foi divido em dois diretorios: **db** e **wiki**. Em cada diretório existe um arquivo **docker-compose.xml** com as configurações de inicialização do container.

* Inicilização de rede para comunicação dos containers

```
docker network create containers-network  
```

* Inicialização do container de Banco de dados:

Acesse o diretorio db e execute o comando:
```
docker-compose up -d --build
```
* Inicilização do container do Wiki.js

Acesse o diretorio wiki e execute o comando:
```
docker-compose up -d --build
```

* Pronto, agora é só acessar [localhost](http://localhost) e usufruir a aplicação.

## 🛠️ Construído com

* [Docker](https://docs.docker.com/) - Criação e administação de containers.
* [Postgresql](https://www.postgresql.org/docs/11/index.html) - O Banco de dados utilizado. 
* [Wiki.js](https://docs.requarks.io/) - Aplicação Web Wiki.js.

## ✒️ Autor

* **Marcos Alves** - *Desafio Wiki.js* - [Marcos Alves](https://github.com/mviniciius29)

