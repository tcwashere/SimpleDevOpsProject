# AWS CI/CD Jenkins/Kubernetes Pipeline

<img src="/DevOps.png" alt="CI/CD Image" title="CI/CD Pipe Line">

---

# Instructions
Design a Jenkins CI/CD application deployment pipeline to Kubernetes on the AWS infrastructure. Users may use any basic "Hello World" application for deployment.

## Requirements

- AWS Infrastructure
- VPC following AWS best practice with public and private subnets
- Jenkins
- GitOps or equivalent
- EKS

## Requirements Overview

1. Developers check-in code to Git repo
2. Upon Git check-in Jenkins build starts
3. Jenkins build pushed docker image to ECR
4. Jenkins deploy application image to EKS
5. User should be able to test deployed application with browser
6. Project time to develop this CI/CD project is within 3 days
