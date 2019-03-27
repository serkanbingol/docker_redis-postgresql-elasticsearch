
## Working with Docker-Compose

- In the root directory of the project run "**docker-compose up**" command.
- Wait all containers to start.
- To run continuously all containers run  "**docker-compose up -d**" command.
- To shut-down all containers run  "**docker-compose down**" command.



## Table for credentials

|  Container  |        Port         |Username|Password|
|:-----------:|:-------------------:|:------:|:------:|
|    Redis    |http://localhost:6379| -----  | -----  |
|Elasticsearch|http://localhost:9200| -----  | -----  |
| PostgreSql  |http://localhost:5432|postgres|postgres|


## Check containers status

- After containers is up, run "**docker container ls**" to see their status
- run ```telnet localhost 5432``` , ```telnet localhost 9200```  , ```telnet localhost 6379``` to get response from containers


## Persistent Data - Backup and Restore Named Volume

**PostgreSql Backup**

- Will be Added

**PostgreSql Restore**

- Will be Added

**Elasticsearch Backup**

- Will be Added

**Elasticsearch Restore**

- Will be Added


## Compose Up Sample Screencast

![compose-up.gif](https://github.com/bilgeadamdev/docker_redis-postgresql-elasticsearch/blob/master/images/up_redis-postgresql-elasticsearch.gif)

## Compose Down Sample Screencast

![compose-down.gif](https://github.com/bilgeadamdev/docker_redis-postgresql-elasticsearch/blob/master/images/down_redis-postgresql-elasticsearch.gif)


