# RuDis APP

## Nest.js | React.js | NGINX | Docker

## Frontend Stack

### Typescript, React.js, Zod, Zustand, Formik, Tanstack ReactQuery, React Router Dom, SCSS

## Backend Stack

### Typescript, Nest.js, PostgreSQL, rxjs, socket.io, TypeORM, Redis

# Project setup (production)

1. Run git clone https://github.com/parismay-code/rudis-app.git
2. Run git submodule update --init
3. Run cp .env.example .env
4. Fill .env variables

### Run application in production environment

1. Run docker-compose -f docker-compose.yml up --build -d

### Run application in development environment (with watcher)

1. Run docker-compose -f docker-compose.dev.yml up --build -d

- If application is running in development environment, any submodule changes will automatically restart docker
  containers