# Private Cloud Infrastructure

## Kubernetes Cluster

The Kubernetes cluster is managed using ArgoCD, which allows for GitOps-based deployment and management of applications and infrastructure.

## Setup Docker Containers

- Create a .env file following the .env.example file and fill in the required values.
- Then run the following command to start the containers:

```bash
docker compose up -d
```

## Backup And Restore

https://mariadb.com/kb/en/container-backup-and-restoration/

## Setting up SSL certificate for nginx web server
