<h1 align="center">:rocket: Aplicação no NodeJS</h1>

## :memo: Descrição
Este é o back-end da nossa aplicação.

## :books: Funcionalidades
* <b>Autenticação de usuário</b>: Usando o OAuth App do GitHub conseguimos autenticar um usuário usando o aplicativo;
* <b>Criação de uma mensagem</b>: Conseguimos inserir uma nova mensagem na nossa aplicação;
* <b>Filtragem de mensagens</b>: Aparecerão as três mensagens mais recentes do nosso banco de dados.

## :wrench: Tecnologias utilizadas
* npm;
* node.js;
* express;
* prisma;
* socket.io;
* typescript;
* github oauth;

## :rocket: Rodando o projeto
O primeiro passo é clonar este repositório para a sua máquina local e, em seguida crie um arquivo chamado .env e insira as informações:
```
GITHUB_CLIENT_ID=
GITHUB_CLIENT_SECRET=
JWT_SECRET=
```
Consiga essas informações ao criar um OAuth App novo nas configurações de desenvolvedor no seu perfil do GitHub.

Então dê o comando a seguir no terminal do seu projeto:
```
npm install
```

E rode a aplicação dando o seguinte comando:
```
npm run dev
```
