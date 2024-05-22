Prerequisites

Node.js installed on your machine
PostgreSQL installed and running

Setup Instructions

Clone the repository
Clone the project repository from the provided URL or download the source code.

Install dependencies

Navigate to the project directory in your terminal.
Run the command npm install to install all the required dependencies.

Set up the database

Create a new PostgreSQL database named task_manager.
In the db.js file, update the database credentials with your PostgreSQL username and password.
In the auth.js file, replace the placeholder 'your_secret_key' with a secure secret key of your choice.
Connect to your PostgreSQL database and run the SQL queries provided in the project's documentation to create the required users and tasks tables.

Build the project

Run the command npm run build to build the project.
Start the server
Run the command npm start to start the server.
The server should now be running at http://localhost:3000.

Running the Application

Open the public/index.html file in your web browser.
You can now register a new user, log in, and manage your tasks.
If you want to deploy the backend to a hosting platform like Heroku, you'll need to configure the database connection accordingly. Follow the instructions provided in the project's documentation.
For the frontend, you can host the public directory on a static file hosting service like Netlify or GitHub Pages.
Make sure to update the API_BASE_URL variable in the public/script.js file to match the URL of your hosted backend API.
