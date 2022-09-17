<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="50" alt="Nest Logo" /></a>
</p>
```bash
nest g res pokemon --no-spec

Nestjs, integration con mongodb:
yarn add @nestjs/mongoose mongoose

las entidades hacen referencia a como nosotros queremos nuestras bases de datos

# nestjs-03-pokedex

# Ejecutar en desarrollo

1. Clonar el repositorio
2. Ejecutar

```
yarn install
```

3. Tener Nest CLI instalado

```bash
npm i -g @nestjs/cli
```

4. Levantar la base de datos

```bash
docker-compose up -d
```

5. clonar archivo **.env.template** y renombrar la copia a **.env**

6. Llenar las variables de entorno definidas en el **.env**

7. Ejecutar la app en dev:

```bash
yarn start:dev
```

8. Reconstruir la base de datos con la semilla

```
http://localhost:3000/api/v2/seed

```

## Stack usado

- MongoDB
- Nest

```

```
