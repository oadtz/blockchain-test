# Blockchain Test

This is a Node.js application that can be easily set up and run using Docker Compose. The application is accessible via a web browser and also includes Maildev for testing and viewing emails sent by the application.

## Prerequisites

Before you begin, ensure you have Docker and Docker Compose installed on your machine. These are required to build and run the containers for the application and Maildev.

## Getting Started

Follow these steps to get the application up and running on your local machine.

### Step 1: Clone the Repository

Clone this repository to your local machine using Git.

### Step 2: Start the database server and mail server

Run Docker Compose to build and start the containers. You can choose one of the following commands:

`docker-compose up`

or

`docker-compose up --build`

### Step 3: Start the Application

Run the following commands:

`npm run dev`

### Step 3: Access the Application

Once the application is running, you can access it in your web browser:

- Application URL: [http://localhost:3000](http://localhost:3000)

### Step 4: Access Maildev

Maildev is set up for handling and viewing emails sent by the application. Access Maildev at:

- Maildev URL: [http://localhost:1080](http://localhost:1080)

---

Enjoy using the application!
