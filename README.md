\# DevOps Frontend Project



A simple static frontend application with a complete containerized CI/CD workflow using GitHub Actions, Docker, GitHub Container Registry, Kubernetes manifests, and Helm.



\## Project Architecture



Developer

&#x20;   ↓

GitHub Repository

&#x20;   ↓

GitHub Actions

&#x20;   ↓

HTML Validation

&#x20;   ↓

Docker Build

&#x20;   ↓

GitHub Container Registry (GHCR)

&#x20;   ↓

Docker Image

&#x20;   ↓

Kubernetes / Helm



\## Technologies Used



\- HTML

\- Git

\- GitHub

\- GitHub Actions

\- Docker

\- Nginx

\- GitHub Container Registry (GHCR)

\- Kubernetes

\- Helm

\- AWS EKS configuration



\## Project Structure



```text

devops/

├── .github/

│   └── workflows/

│       └── ci.yml

├── helm/

│   ├── Chart.yaml

│   ├── values.yaml

│   └── templates/

├── k8s/

│   ├── deployment.yaml

│   └── service.yaml

├── Dockerfile

├── index.html

└── README.md

