# Terraform Docker Nginx Deployment

## Overview

This project demonstrates how to use Terraform to provision and manage an Nginx Docker container.

## Technologies Used

- Terraform
- Docker
- Nginx
- Ubuntu
- AWS EC2

## What I Did

1. Installed Terraform on an Ubuntu EC2 instance.
2. Configured the official HashiCorp repository.
3. Configured the Docker provider in Terraform.
4. Pulled the Nginx Docker image using Terraform.
5. Created an Nginx Docker container using Terraform.
6. Mapped port 8080 on the host to port 80 in the container.
7. Validated and applied the Terraform configuration.
8. Verified the running container using Docker.
9. Tested Nginx using `curl`.

## Terraform Commands

```bash
terraform init
terraform validate
terraform plan
terraform apply
