# DevSecOps Lab

This is a personal DevSecOps learning project simulating a real production pipeline.

## Dockerized NGINX App

- Dockerfile for basic NGINX app
- Custom nginx.conf
- Runs on port 8080

To build and run:

```bash
cd app
docker build -t devsecops-lab-nginx .
docker run -d -p 8080:80 devsecops-lab-nginx
curl http://localhost:8080
