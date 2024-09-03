This repository contains the analytics-api microservice, which includes its application code, configuration files, and dependencies specified in the `requirements.txt` file. The dependencies are installed during the containerization process as specified in the `Dockerfile`. The `buildspec.yml` file outlines the steps for building the Docker image. This process involves logging into AWS Elastic Container Registry (ECR), building the Docker image according to the Dockerfile instructions, tagging the image, and pushing it to ECR. 

### The application's primary purpose is to monitor and report user activity in a system, specifically:

- Tracking and reporting daily usage data.
- Tracking and reporting individual user visits.
- Ensuring the service's health and readiness for serving requests.
- This setup could be part of a larger system for analytics, user engagement tracking, or monitoring application usage over time.
