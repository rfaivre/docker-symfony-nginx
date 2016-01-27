# Docker-compose with Nginx, PHP-FPM and Mysql

Setup for quickly docker containers.

### Build and run containers

```
docker-compose build
docker-compose up -d
```

### Remove containers
```
docker-compose rm -v
```

### Execute a command in a container
```
docker exec -ti <container_name> <command>
```
