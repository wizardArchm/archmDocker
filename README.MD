# Archm

## Archm docker

The componse file including those containers down here:

* redis
* postgre
* rabbit
* mongo
* nexus
* jenkins
* minio

### Redis

Is used by archm gateway as session storage database and may be used by other project as cache database.

### postgre

A PostgreSQL container, used by archm consumer project as database.

### rabbit

A RabbitMQ container, used by all project as MQ component.

### Mongo

A MongoDB container. Not used by any project currently. But I will show how to combine mongoDB with Node server.

### Nexus

As the official website said.

> The world's first and only universal repository solution that's FREE to use. 

I will use nexus as a maven repository, so that I can publish my java library to a private repository.

### Jenkins 

I will show you how to config jenkins with pipeline by writing jenkins file.

### Minio

A object storage system, which is compatible with amazon S3 perfectly.
