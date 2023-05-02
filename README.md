# SQL_Training
The files here are used in the setup and running of a self-designed postgres SQL training session. The data is based off the R package nycflights13 but has been converted into a format for upload into an postgres SQL database. The introduction training is designed, with the support from the slides (hosted at https://rlh1994.github.io/sql_training_postgres/ ) for users with no experience at all to take them to being able to write the majority of queries they will need. The focus is on being able to work with and access data already in a database, rather than on database management.

The answers to exercises are provided as a guidance and as such there may be better or other ways to answer these questions.

Feel free to use the data and training material as you want, but where relevant credit me.

## Setup and Usage
To get started, please ensure you have [docker](https://docs.docker.com/) installed on your machine, docker desktop is also recommended for easier management of containers.

Once docker is installed, simply run `docker compose up`, or `docker compose up -d` to run it detached. This will start a postgres warehouse available on port 5432, with a username of `admin` and a password of `password` - DO NOT USE THIS IN PRODUCTION - and will begin to populate the warehouse with the training data required. This should take a few minutes depending on your hardware and will only need to be done the first time the container is created. You should connect using your preferred tool e.g. VScode or PGadmin.

## Murder Mystery
Based on https://github.com/NUKnightLab/sql-mysteries but adapted for postgres SQL.
