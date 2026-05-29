# GitHub Account API

> Status: Em desenvolvimento ⚠️

## 📖 Sobre o projeto

API REST desenvolvida com Node.js, Express, Sequelize e SQLite para prática de conceitos de desenvolvimento back-end, como operações CRUD, rotas REST, persistência de dados e relacionamento entre entidades.

O projeto simula algumas funcionalidades básicas do GitHub, incluindo contas, repositórios, seguidores e estrelas.

---

## 🚀 Tecnologias

* Node.js
* Express
* Sequelize
* SQLite
* JavaScript

---

## 📌 Funcionalidades

### Accounts

* Criar contas
* Atualizar informações de contas
* Remover contas
* Listar contas

### Followers

* Seguir/deixar de seguir contas
* Listar seguidores

### Repositories

* Criar repositórios
* Atualizar repositórios
* Remover repositórios
* Listar repositórios

### Stars

* Adicionar estrelas em repositórios
* Remover estrelas

### Login e Tokens

* Simulação de login
* Criação de registro de login através de Token

---

## 🗂 Modelos da aplicação

### Account

* id
* nome
* email
* local
* avatar
* username
* bio

### Follower

* id
* follower_username
* followed_username

### Repository

* id
* nome
* description
* public
* user_id

### Star

* id
* user_id
* repository_id

### Token

* id
* data
* user_id

---

## ▶️ Como executar o projeto

### Instalar dependências

```bash
npm install
```

### Executar a aplicação

```bash
node app.js
```

A API será executada em:

```bash
http://localhost:3000/
```

---

## 📚 Rotas

👉 Veja todas as rotas aqui:

[ROTAS.md](https://github.com/samueldantasoliveira/API-EXAMPLE/blob/main/ROTAS.md)
