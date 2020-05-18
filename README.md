# Up and Running

docker-compose -d

# Check Whether contain is running

docker-compose ps

# enter the shell

docker-compose run db bash

## Verify db exist

poql --host=db --username=alice --dbname=myawesomedb

## Esc the db

Ctrl + d twice

# Off

docker-compose down
