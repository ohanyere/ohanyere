# Francis Ohanyere

Platform-focused engineer with a strong foundation in backend development and growing expertise in cloud-native infrastructure. I build and operate systems that are reliable, scalable, and production-ready.

My work sits at the intersection of backend engineering and platform engineering—designing APIs, provisioning infrastructure with Terraform, and deploying workloads on Kubernetes (EKS).

I focus on solving practical problems around system reliability, deployment automation, and infrastructure efficiency.

## Core Focus

* Designing and deploying cloud-native applications on AWS (EKS)
* Building modular infrastructure using Terraform (VPC, networking, compute)
* Developing backend services in Go with clean, maintainable architecture
* Containerizing and orchestrating applications with Docker and Kubernetes
* Implementing CI/CD pipelines and GitOps workflows
* Improving system observability using Prometheus and Grafana
* Optimizing infrastructure cost and workload efficiency

## Tech Stack

Infrastructure & Cloud:

* AWS (EKS, EC2, VPC, IAM, ALB)
* Terraform (modular architecture, reusable modules)

Containerization & Orchestration:

* Docker
* Kubernetes (Deployments, Services, Ingress)

Backend:

* Go (Golang)
* REST APIs
* Redis, PostgreSQL

CI/CD & GitOps:

* GitHub Actions
* ArgoCD

Observability:

* Prometheus
* Grafana
* Loki (basic usage)

Other:

* Linux (Ubuntu)
* Git

## Current Direction

* Building a cloud-native platform project combining:

  * Go services (API + worker architecture)
  * Kubernetes (EKS) deployments
  * Terraform-managed infrastructure
  * Observability stack (Prometheus + Grafana)

* Exploring workload efficiency and cost optimization in Kubernetes environments

* Deepening understanding of:

  * Kubernetes scheduling and scaling
  * Infrastructure design patterns
  * Production-grade system reliability

## Selected Work

You’ll find projects here that reflect:

* Real-world infrastructure setups (not tutorials)
* End-to-end systems (infra → app → deployment)
* Practical debugging and operational experience

## Contact

* Email: [ohanyerefrancis395@gmail.com](mailto:ohanyerefrancis395@gmail.com)
* GitHub: https://github.com/ohanyere

---

## Example Workflow

# Provision infrastructure
terraform init
terraform apply

# Configure cluster access
aws eks update-kubeconfig --name company-prod-eks --region us-east-1

# Deploy workloads
kubectl apply -f k8s/

# Observe system
kubectl get pods -A
