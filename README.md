# Dockerized MySQL

* [MySQL](https://hub.docker.com/_/mysql/).

## Build steps
* Change `.env-demo` to `.env` and set values.

```bash
APP_NAME=app

# mysql
PERSISTENT_DATA=./persistent-data
MYSQL_HOST=mysql

# docker mysql environment variables
# required.
MYSQL_ROOT_PASSWORD=secret
MYSQL_DATABASE=database
MYSQL_USER=user
MYSQL_PASSWORD=secret
```

* Run `docker-compose up` (needs [Docker Compose](https://docs.docker.com/compose/) installed).

Once running mysql is on 0.0.0.0:3306 and also mysql:3306.


## Requirements
* [Docker Engine](https://docs.docker.com/installation/).
* [Docker Compose](https://docs.docker.com/compose/).
* [Docker Machine](https://docs.docker.com/machine/) (Mac and Windows only).