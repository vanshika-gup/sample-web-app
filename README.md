# Author
Vanshika Gupta
G23AI2050
PGD-DE Cohort-2

# Sample Web Application

This is a simple Node.js web application deployed using Docker.

## Application Functionality

The application listens on port 3000 and returns "Hello World!" when accessed.

## How to Build and Run
1. Create and Setup Project Directory: Create a directory sample-web-app, navigate into it, and initialize a Node.js project with npm init -y.
Install Express with npm install express.

2. Create Web Application:Create an app.js file with a simple Express server that responds with "Hello World!" on the root route.

3. Create Dockerfile:Create a Dockerfile to build a Docker image, specifying the Node.js base image, working directory, copying project files, installing dependencies, exposing port 3000, and setting the startup command.

4. Build and Run Docker Image: Build the Docker image with docker build -t sample-web-app . and run it with docker run -p 3000:3000 sample-web-app.

5. Finally push it to github

### Prerequisites

- Docker
- Node.js


