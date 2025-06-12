# 🐳 Dockerized React + Django App

This is a full-stack web application built using **Django (Backend)** and **React (Frontend)**, fully containerized using Docker.

## 🚀 How to Run (Dockerized)

> Make sure Docker is installed.

```bash
# Build the Docker image
docker build -t django-app .

# Run the container
docker run -p 8000:8000 django-app
```

The Django app will be accessible at:  
🌐 http://localhost:8000/

## 🔧 Tech Stack

- **Backend:** Django
- **Frontend:** React.js
- **Containerization:** Docker
- **Deployment:** AWS EC2 (Free Tier – instance terminated after testing)

## 📘 Notes

This project was cloned from a mentor's repo, dockerized, and deployed on an EC2 instance for educational and portfolio purposes. The EC2 instance has been terminated to avoid billing on the free tier.

## 🌟 Star this repo if you found it helpful!
