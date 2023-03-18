<h1>URL Shortener</h1>

This is a simple URL shortener web application built with Node.js, MongoDB, and Express. The purpose of this application is to shorten long URLs into shorter ones that are easier to share and remember.

Installation
Clone the repository or download the ZIP file.
Install Node.js and MongoDB if you haven't already.
Open a terminal and navigate to the project directory.
Run npm install to install the dependencies.
Rename .env.example to .env and set your own values for the environment variables.
Run npm start to start the server.
Usage
Once the server is running, you can access the web application by visiting http://localhost:3000 in your web browser. You can enter any long URL in the input field and click on the "Shorten" button to generate a shorter URL. You can then copy the shorter URL and share it with others.

The application also provides a RESTful API for creating and retrieving short URLs. You can make HTTP requests to the following endpoints:

POST /api/urls to create a short URL
GET /api/urls to retrieve a list of all short URLs
GET /api/urls/:id to retrieve a specific short URL by ID

