# SimbliMongoSetup
Docker compose setup with init mongodb

## To run the Postgres Database:
- Clone this repo.
- Run docker-compose up.
- This will install mongodb, create the database as per defined in the docker-compose.yml.

## To shutdown database alone:
- Run docker-compose down

###### To Remove the volume along with shutdown (required for creating tables again on docker compose up):
- Run docker-compose down -v db 
