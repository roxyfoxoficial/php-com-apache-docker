# PHP com Apache2 no Docker

Criando um site com PHP e subindo na porta 80 com Apache2. Tudo isso dentro de um container docker rodando na porta 3000

## Requisitos

- Docker
- Docker Compose

## Como Iniciar

> Iniciando Container docker

```sh
docker-compose up -d
```

> Acessar página

```sh
curl http://localhost:3000
```
