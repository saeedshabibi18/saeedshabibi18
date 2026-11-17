<div align="center">
 
# Hi there, I'm Saeed Shabibi 👋
 
### 🚀 DevOps & Cloud Engineer | AWS | Docker | Kubernetes | Linux
 
*"Automate everything. Document everything. Ship it."*
 
</div>
---
 
## 👨‍💻 About Me
 
I'm a final-year B.Tech student passionate about building, deploying, and managing scalable cloud infrastructure. I love automating things, containerizing applications, and making systems run smoother.
 
- 🎓 Completing my B.Tech degree (May 2026)
- 🔍 Actively looking for **DevOps Engineer / Cloud Engineer** roles (Fresher / Internship)
- 📚 Deepening my Kubernetes and AWS knowledge every day
---
 
## 🛠️ Tech Stack
 
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Shell Script](https://img.shields.io/badge/Shell_Scripting-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
 
---
 
## 📂 Featured Projects
 
### 💰 AWS EBS Snapshot Cost Optimization
 
> A serverless automation that finds and deletes unnecessary EBS snapshots to cut AWS storage costs, built with **AWS Lambda** and **Python (Boto3)**.
 
**Problem:** When EBS volumes are deleted, their snapshots often stay behind, silently adding to the monthly AWS bill.
 
**Solution:** A Lambda function scans snapshots, checks whether each source volume still exists, and removes the ones that are no longer needed.
 
**How it works:**
 
1. Lambda retrieves all EBS snapshots owned by the AWS account.
2. For each snapshot, it checks whether the original EBS volume still exists.
3. Snapshots whose volume was **deleted** are identified.
4. Snapshots linked to **unattached** volumes are also identified.
5. The unnecessary snapshots are deleted automatically.
6. CloudWatch logs record execution and deletion activity for monitoring.
**Highlights:**
 
- ✅ Fully serverless, with no servers to manage
- ✅ Reduces wasted EBS storage spend automatically
- ✅ Least-privilege access through AWS IAM
- ✅ Execution and deletions tracked in CloudWatch
**Stack:** Python · Boto3 · AWS Lambda · EC2 · EBS · IAM · CloudWatch
 
---
 
### ⛅ [Flask Weather App: CI/CD Pipeline with Docker, GitHub Actions & AWS EC2](https://github.com/saeedshabibi18/weather-application)
 
> A production-grade Flask Weather Application with a complete 3-stage CI/CD pipeline. Every push to GitHub automatically tests, builds, and deploys the app to AWS EC2 with zero manual steps.
 
**Pipeline stages:**
 
| Stage | What happens |
|-------|--------------|
| 1️⃣ Test | Automated health check and route validation |
| 2️⃣ Build | Multi-stage Docker build and push to Docker Hub |
| 3️⃣ Deploy | Auto deploy to AWS EC2 via SSH with health verification |
 
**Highlights:**
 
- 📉 Reduced Docker image size by **60%** using an Alpine Linux multi-stage build
- 🔐 Secured **6 credentials** with GitHub Secrets, with zero hardcoded keys
- 🌦️ Live weather data for any city via the WeatherAPI.com REST API
**Stack:** Python · Flask · Docker · GitHub Actions · AWS EC2 · Docker Hub · Gunicorn · Linux
 
---
 
### 🐳 [Dockerized Node.js App with MongoDB](https://github.com/saeedshabibi18/DevOps_Projects)
 
> Containerized a full-stack Node.js application using Docker and Docker Compose, integrating MongoDB and Mongo Express for database management. Demonstrates multi-container orchestration and service networking.
 
**Stack:** Docker · Docker Compose · MongoDB · Node.js
 
---
 
### ☁️ [AWS DevOps Hands-On Journal](https://github.com/saeedshabibi18/AWS-learning--journal)
 
> A structured, self-maintained record of real AWS implementations, including:
 
- Flask web app deployment on EC2 (Amazon Linux)
- Dockerized Flask app deployed on AWS
- Docker Swarm two-node cluster setup
- EC2 Auto Scaling and CloudWatch monitoring
- Docker Compose on cloud infrastructure
**Stack:** AWS EC2 · Docker · Docker Swarm · Flask · Linux · CloudWatch
 
---
 
## 📫 Let's Connect
 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-LINKEDIN-HERE)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR-EMAIL-HERE)
 
---
 
<div align="center">
⭐ Thanks for visiting my profile!
 
</div>
 
