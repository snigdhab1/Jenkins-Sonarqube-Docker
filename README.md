# SimpleTimeService

## Description
SimpleTimeService is a minimal microservice that provides the current timestamp and visitor's IP in JSON format.

## Deployment Instructions

### Prerequisites
- Docker
- Kubernetes cluster
- `kubectl` configured for your cluster

### Steps

1. Build and push the Docker image (optional if already published):
   ```bash
   docker build -t <your-dockerhub-username>/simple-time-service:latest .
   docker push <your-dockerhub-username>/simple-time-service:latest
