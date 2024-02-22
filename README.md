Create a custom network to put 2 apps in the same network by command
```
docker network create jar-container-network
```

Use docker-compose.yml file to run those 2 services in 1 container

```
docker compose up --build
```
