## Running MySQL

```sh
docker run -d -p 3306:3306 --name mysql -e MYSQL_ROOT_PASSWORD=root mysql
docker exec -it mysql mysql -uroot -proot -e 'CREATE DATABASE todolist'
```

## Running backend

```sh
cd ./backend
go run .
```

## Running frontend

```sh
cd ./backend
go run .
```
