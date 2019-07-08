# Symfony Mercure
Example how to get up and running with symfony mercure

## Install Symfony
docker run --rm -it -v $PWD:/app composer create-project symfony/website-skeleton symfony_mercure

## Install the Mercure component
docker run --rm -it -v $PWD:/app composer require mercure

## Run the infrastructure
docker-compose up