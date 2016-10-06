# Docker

## Install
Install docker and [docker-compose](https://docs.docker.com/compose/install/)

```
cd path/to/you/project
git clone https://github.com/pahanium/docker.git
cp docker/docker-compose.yml .
```

## Run
```
docker-compose up -d
```

## Test
Open url [http://localhost:8080](http://localhost:8080) and you will see you app

To run php command in app:
```
docker-compose run app web
```