# spring-boot-mongodb
This repository contains a Spring Boot example project for MongoDB.

For a code review of this repo, see my related [blog post](https://springframework.guru/3402-2/).

You can learn more about my courses [here](http://courses.springframework.guru/courses/) on my site.

Docker commands
docker run -p 27017:27017 -v ~/dockerdata/mongo/:/data/db -d mongo
docker run -d --hostname my-rabbit --name some-rabbit rabbitmq
docker run -d --hostname my-rabbit --name some-rabbit -p 8081:15672 rabbitmq:management
docker run --name some-mysql -e MYSQL_ALLOW_EMPTY_PASSWORD=yes -v ~/dockerdata/mysql/:/data/db -p 3306:3306 -d mysql