# Infrastructure description

!["Architecture diagram"](../diagrams/Architecture%20diagram.jpg "Architecture diagram")

### The infrastructure of the application uses Elasticbeanstalk for hosting the API and an s3 bucket to host the front end of the application and uses the RDS service to save data on a postgreSQL database.

#### The steps of the process are as follows:
- The User goes on the site 
- The front-end (created using angular) fetches data and sends it to the API hosted on Elasticbeanstalk
- The API save the data on the RDS which has a postgres database ready to save it.