# Django Backend Docker Container

This repository contains the configuration for running a Django backend server in a Docker container.

## Prerequisites

Make sure you have Docker installed on your system. If not, you can follow the installation instructions for your operating system [here](https://docs.docker.com/get-docker/).

## Usage

### Build Docker Image

To build the Docker image for the Django backend, run the following command:

```bash
sudo docker build -t my-django .

### Run Docker Container

To run the Docker container with the Django backend server, use the following command:

```bash
sudo docker run -p 8000:8000 my-django

### Access the Server

Once the container is running, you can access the Django server by navigating to http://localhost:8000 in your web browser.
