# Dockerized Node.js Express API

This repository contains a simple Node.js Express REST API that returns a "Hello, World!" response. It also includes Dockerfiles and docker-compose configurations to containerize and run the API using Docker.

## Prerequisites

- [Node.js](https://nodejs.org/) installed on your local machine
- [Docker](https://www.docker.com/) installed on your local machine (optional, if you want to run the application using Docker)

## Getting Started

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/shaifali15/Devops-assignment.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Devops-assignment
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Start the API locally:

    ```bash
    node main.js
    ```

    You can access the API at [http://localhost:3000](http://localhost:3000) in your web browser.

## Docker Usage

If you prefer to run the application using Docker, follow these steps:

1. Build the Docker image:

    ```bash
    docker build -t node-api .
    ```

2. Run a container using the created image:

    ```bash
    docker run -p 3000:3000 node-api
    ```

    You can access the API at [http://localhost:3000](http://localhost:3000) in your web browser.

Alternatively, you can use Docker Compose:

1. Build and start the container using Docker Compose:

    ```bash
    docker-compose up
    ```

    You can access the API at [http://localhost:3000]
