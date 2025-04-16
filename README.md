# SIT323-2025-Prac5D: Kubernetes-Deployed Node.js Microservice

This repository contains the code and configuration for deploying a simple Node.js microservice using Kubernetes. The project is part of the **SIT323/SIT737 - Cloud Native Application Development** unit at Deakin University.

## 🛠️ Tech Stack

- Node.js
- Express.js
- Docker
- Kubernetes (Minikube)
- Docker Hub (for image hosting)

## 📁 Project Structure

| File              | Description                                          |
|-------------------|------------------------------------------------------|
| `index.js`        | Core Node.js server using Express                   |
| `package.json`    | Node.js dependencies and metadata                   |
| `Dockerfile`      | Instructions to containerize the app using Docker   |
| `deployment.yaml` | Kubernetes Deployment configuration (2 replicas)    |
| `service.yaml`    | Kubernetes NodePort service exposing the app        |

## 🚀 How to Run the App on Minikube

### 1. Start Minikube
```bash
minikube start
