# pg-docker-env
pg-docker-env is a repo to setup docker image of postgres on local environment

### running postgres in docker
On root for initial build and start
```bash
docker-compose up --build
```
On root to start intance
```bash
docker-compose up
```
This will run postgres database in docker.
If a new docker image is created, script/init contains files for table creation '1-schema.sql' and table data initialisation '2-data.sql'.
Use values in docker-compose.yaml to set up the service, instance, credentials, ports of the database.
