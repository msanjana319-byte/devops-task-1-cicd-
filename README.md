
# DevOps Task 1: CI/CD Pipeline

## Overview
Created a Node.js application and automated its Docker image build and push to Docker Hub using GitHub Actions.

## Tools Used
- Node.js
- Docker and Docker Hub
- GitHub Actions
- GitHub

## Work Completed
1. Created a Node.js application.
2. Created a Dockerfile to containerize the application.
3. Configured a GitHub Actions CI/CD workflow.
4. Built and pushed the Docker image to Docker Hub.
5. Pulled and ran the image locally using Docker Desktop.
6. Verified the running container using `docker ps`.

## Docker Image
`sanjanaa12/nodejs-demo-app:latest`

## Run the Application
```bash
docker pull sanjanaa12/nodejs-demo-app:latest
docker run -d -p 3000:3000 --name nodejs-demo-app sanjanaa12/nodejs-demo-app:latest
```

Open http://localhost:3000 in your browser.

## Screenshots
Project screenshots are available in the `screenshots` folder.
