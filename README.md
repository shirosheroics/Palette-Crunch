# Palette-Crunch

## Requirements:

- docker >= 17.12.0+
- docker-compose

## Quick Start

- Clone or download this repository
- Go inside of directory, `cd Palette-Crunch`
- Run this command `docker-compose up --build`

## Structure

- frontend: a simple react app can be accessed at http://localhost:3000/
- backend: a simple flask server can be accessed at 0.0.0.0:5000
- database: a postgres database
- pgAdmin: administration page for postgres can be accessed at http://localhost:5050
  -- when you access the page it will request a password you can set it to "admin"
  -- add new server and fill the information as follows:
  --- under general you can set name to database
  --- under connection Hostname is "database" the name of the service in the docker-compose file and password is "changeme"
- redis
