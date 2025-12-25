🐳 Docker Basics – Learning Repo

This repository documents my hands-on learning with Docker, focusing on containerizing a simple web application and understanding the core Docker workflow.

🚀 What I Learned

What Docker is and why containers beat “it works on my machine”

Difference between Docker Image vs Container

Writing a basic Dockerfile

Building images using docker build

Running containers with docker run

Port mapping (-p host:container)

Container lifecycle: start, stop, remove

Debugging common issues (port conflicts, container not running)

🧩 Mini Project

Containerized a simple Flask web app

Exposed the app using Docker port mapping

Verified isolation and reproducibility

🛠️ Tech Stack

Docker

Python (Flask)

HTML (basic UI)

📦 Key Commands Used
docker build -t my-app .
docker run -p 5000:5000 my-app
docker ps
docker stop <container_id>
docker rm <container_id>

🎯 Why This Matters

Docker ensures consistent environments, faster setup, and smoother deployment—essential for modern DevOps, ML pipelines, and production-ready apps.
