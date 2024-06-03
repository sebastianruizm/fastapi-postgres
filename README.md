# fastapi-postgres
Lectura y escritura en base de datos Postgres con FastAPI

## Quickstart

En este ejemplo utilicé GitHub Codespaces pero también se puede ejecutar localmente

### 0 Add port

Solo para GitHub Codespaces

![0-1](assets/images/00-add-port1.png)

![0-2](assets/images/00-add-port2.png)

### 1 Build

Ejecutar docker-compose mediante Makefile

```bash
make build
```

![1-1](assets/images/01-make-build1.png)

### 2 Check Postgres

Validar que Postgres se está ejecutando correctamente

![2-1](assets/images/02-check-postgres1.png)

### 3 Check FastAPI

Validar que FastAPI se está ejecutando correctamente

http://0.0.0.0:8000

![3-1](assets/images/03-check-fastapi1.png)

![3-2](assets/images/03-check-fastapi2.png)

### 4 FastAPI Docs

Acceder a FastAPI docs para interactuar con la base de datos Postgres

http://0.0.0.0:8000/docs

![4-1](assets/images/04-fastapi-docs1.png)

### 5 API POST

Insertar registro en la base de datos mediante método POST

![5-1](assets/images/05-fastapi-post1.png)

![5-2](assets/images/05-fastapi-post2.png)

### 6 API GET

Consultar registro en la base de datos mediante método GET

![6-1](assets/images/06-fastapi-get1.png)

![6-2](assets/images/06-fastapi-get2.png)

### 7 Validate Postgres

Validar datos en Postgres

![7-1](assets/images/07-validate-postgres1.png)