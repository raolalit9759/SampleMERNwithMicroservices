# SampleMERNwithMicroservices
SampleMERNwithMicroservices
For helloService, create .env file with the content:

PORT=3001
For profileService, create .env file with the content:

PORT=3002
MONGO_URL="specifyYourMongoURLHereWithDatabaseNameInTheEnd"
Finally install packages in both the services by running the command npm install.


For frontend, you have to install and start the frontend server:
cd frontend
npm install
npm start
Note: This will run the frontend in the development server. To run in production, build the application by running the command npm run build
