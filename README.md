# Starter kit for Building A REST API With Node, Express, TypeScript & MongoDB


This is a repository for a build REST API using Node, Express, Typescript & MongoDB.


Features:

- Environment, Typescript, Nodemon setup
- MongoDB & Mongoose connect, Database creation
- Controllers creation
- Middlewares creation
- Cookie based authentication
- Postman testing
- Create, Read, Update

### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone https://github.com/umanda/experess-ts-api-starter.git
```

### Install packages

```shell
yarn 
```

### Setup MongoDB URL

In `src/index.ts`:

```js
const MONGO_URL = ''; // DB URI
```

### Start the app

```shell
yarn start
```

## Available commands

Running commands with npm `yarn run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `start`         | Starts a development instance of the app |

### Start the app

### TODO
- Add env file. 
- Add redis for auth.
- Add Role based auth.
- Add Multiple DB support - PGSQL
- Add Multiple DB support - MySQL
- Add oAUth Login
- Add JWT Login
- Add Social Login
- Add Open API Documentation
- Add Docker

