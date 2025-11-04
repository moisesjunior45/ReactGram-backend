# React Gram - Backend

Este é o **backend** do projeto **ReactGram**, responsável por gerenciar autenticação, upload de imagens, conexão com banco de dados e rotas da aplicação. Ele foi desenvolvido com **Node.js**, **Express** e **MongoDB**.

🔗 Frontend do projeto: [ReactGram Frontend](https://github.com/moisesjunior45/ReactGram-frontend)

## Funcionalidades

- Registro e autenticação de usuários com **JWT**  
- Upload de imagens com **Multer**  
- Conexão com banco de dados **MongoDB Atlas**  
- Rotas protegidas por autenticação  
- Middleware de validação de dados com **express-validator**  
- Integração com o frontend via **CORS**  

### Url da Aplicação hospedada

```
  react-gram-blond.vercel.app
```

## Introdução

Estas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

### Pré-requisitos

O que você precisa para instalar o software e como instalá-lo:  

Node.js e o NPM (Node Package Manager) ou Yarn instalados em seu computador

## 🛠️ Como Rodar o Projeto

### Pré-requisitos
- Node.js (>= 18)  
- MongoDB Atlas (ou instância local)  
- npm ou yarn  

### Passos
```bash
# Clone o repositório
git clone https://github.com/moisesjunior45/ReactGram-backend

# Acesse a pasta do projeto
cd reactgram-backend

# Instale as dependências
npm install

# Inicie o servidor com nodemon
npm run server
```
## ⚙️ Configuração de variáveis de ambiente

Este projeto utiliza variáveis de ambiente para armazenar informações sensíveis (como chaves secretas e URLs de banco de dados).

1. Crie um arquivo `.env` na raiz do projeto.
2. Use o arquivo `.env.example` como referência para saber quais variáveis precisam ser definidas.
3. Preencha os valores de acordo com o seu ambiente local.

Exemplo de `.env.example`:


## Tecnologias usadas:

* ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
* ![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
* ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
* ![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logoColor=white)
* ![JWT(JSON Web Token)](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
* ![Multer](https://img.shields.io/badge/Multer-FF6F00?style=for-the-badge&logoColor=white)
* ![Bcrypt.js](https://img.shields.io/badge/Bcrypt.js-0033A0?style=for-the-badge&logoColor=white)
* ![CORS](https://img.shields.io/badge/CORS-FFB400?style=for-the-badge&logoColor=black)
* ![Dotenv](https://img.shields.io/badge/Dotenv-000000?style=for-the-badge&logoColor=green)
* ![Express Validator](https://img.shields.io/badge/Express--Validator-6DB33F?style=for-the-badge&logoColor=white)
* ![Nodemon](https://img.shields.io/badge/Nodemon-76D04B?style=for-the-badge&logoColor=black)


## 👷 Autor

* **Moisés Júnior** - *Fullstack* - [Moisés Júnior](https://github.com/moisesjunior45)



