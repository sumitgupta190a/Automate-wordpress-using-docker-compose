# Automate-wordpress-using-docker-compose
Setting up a Three-Tier Architecture using WordPress and MySQL containers.

BASIC COMMAND

docker-compose -f workpress_full_automate.yml up -d (up means to run the code, -f is for file that we are giving, -d means run the command in deamon mode )

docker-compose -f workpress_full_automate.yml up (up means to run the code -f is for file that we are giving)

docker-compose -f workpress_full_automate.yml ps (To see the container in docker-compose )

mv workpress_full_automate.yml docker-compose.yml (To move the file )

docker-compose up -d (To run this in detached or demonized mode)

docker-compose logs (To see the logs)

docker-compose exec c1 date (Used to run the command inside the container)

docker-compose stop (To stop the docker-compose )
docker-compose -f (file name) stop 

docker-compose rm (For remove the container)
