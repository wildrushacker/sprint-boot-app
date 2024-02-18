# Sample Spring Boot project 

## How to run it
 * Pre-requisite (for first time run only) <br>
  Create a folder for mysql volume mount <br>
  `mkdir -p ~/data/mysql8`

 * Build<br>
   `./gradlew clean build`

 * Run via Docker Compose <br>
   `docker-compose up -d --build --scale application=2`

 
## Creating Dummy Data
 * Run SQL Script - `scripts/Create_Dummy_Data.sql`
 
 
## Default Users for Login
Username|Password|ROLE
--------|--------|-----
admin01@tw.com|admin01@123#|ADMIN
admin02@tw.com|admin02@123#|ADMIN
user01@tw.com|welcome@123#|USER
