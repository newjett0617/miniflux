# docker-compose-template

```
cp .env.example .env
```

edit .env

```
docker network create reverse_proxy
docker network create pgsql
```

```
docker-compose up -d
```
