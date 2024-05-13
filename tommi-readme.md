Config 2 files: database.yml & run.sh

Completely remove postgres, postico, pgadmin, docker from computer (with appcleaner)

Do step by step to create database

Try to connect to database: `jdbc:postgresql://localhost:5432/vigilate`

Migrate: `soda create -e development --debug`
Create dev database: `soda create -e development --debug`

RUN: `./run.sh`