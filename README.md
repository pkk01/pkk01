# Pratham Kumar 👋 | Full Stack • DevOps • System Design
![header](https://img.shields.io/badge/Status-Open%20to%20Internships-blue?logo=briefcase)
![contact](https://img.shields.io/badge/Email-your.email@example.com-green?logo=gmail)
![location](https://img.shields.io/badge/Location-India-orange?logo=googlemaps)

---

<p align="center">
  <img src="https://raw.githubusercontent.com/pkk01/pkk01/main/assets/hero-devops.png" alt="hero" width="700" />
</p>

Hi — I'm Pratham Kumar (pkk01). I'm a 3rd-year B.Tech student and a Full Stack + DevOps engineer-in-training. I build production-minded web applications, design backend systems for scale, and automate cloud infrastructure so teams can ship confidently.

"Code it. Containerize it. Automate it." — my guiding mantra.

---

## Table of Contents
- [Quick Snapshot](#quick-snapshot)
- [What I Do](#what-i-do)
- [Tech Stack](#tech-stack)
- [Featured Projects](#featured-projects)
- [How I Work](#how-i-work)
- [DevOps Playbook (Highlights)](#devops-playbook-highlights)
- [Project Quickstart (LogiShift)](#project-quickstart-logishift)
- [Open Source & Contributions](#open-source--contributions)
- [Roadmap & Learning](#roadmap--learning)
- [Contact & Availability](#contact--availability)
- [Fun Stats](#fun-stats)

---

## Quick Snapshot
- Role: Full Stack + DevOps Engineer (B.Tech — 3rd Year)  
- Focus: System design, cloud infrastructure, Kubernetes orchestration, IaC  
- Strengths: Backend architecture, API-first design, containerized CI/CD pipelines, observability  
- Seeking: Internships, collaborative projects, and mentorship opportunities

---

## What I Do
- Architect and implement RESTful/APIs and scalable backend services.
- Build modern frontends with React and reusable component systems.
- Containerize applications and automate CI/CD with GitHub Actions / Jenkins.
- Provision and manage cloud infrastructure using Terraform and AWS.
- Apply SRE principles to monitor and keep systems resilient.

---

## Tech Stack
A compact view of tools I use regularly.

Frontend
- HTML, CSS, JavaScript, React, Tailwind CSS, Bootstrap

Backend
- Node.js (Express), Django / DRF, Spring Boot, REST APIs, JWT & OAuth patterns

Datastores
- PostgreSQL, MySQL, MongoDB, Redis, Firebase

DevOps & Cloud
- Docker, Docker Compose, Kubernetes (fundamentals)
- AWS (EC2, S3, RDS, IAM), GCP
- Terraform, Ansible, Linux, Shell scripting

CI / CD / Observability
- GitHub Actions, Jenkins, GitLab CI
- Prometheus, Grafana (instrumentation fundamentals)

(Visual badges)
<p align="left">
  <img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=white" /> 
  <img src="https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white" /> 
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" /> 
  <img src="https://img.shields.io/badge/AWS-232F3E?logo=amazon-aws&logoColor=white" /> 
  <img src="https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Postgres-336791?logo=postgresql&logoColor=white" />
</p>

---

## Featured Projects

### LogiShift — Real-time Delivery Tracking
A full-stack delivery tracking platform for monitoring shipments, updating statuses in real time, and visualizing delivery routes.

- Frontend: React (component-driven UI), Tailwind CSS  
- Backend: Django + Django REST Framework  
- Database: PostgreSQL  
- Real-time: WebSockets / Channels (or alternative) for live updates  
- DevOps: Dockerized services, CI/CD pipelines, deployment-ready manifests  
- Highlights:
  - Real-time tracking & notifications
  - Role-based access (admin / driver / user)
  - Modular microservice-ready structure
- Repo: https://github.com/yourusername/logishift (replace with actual link)
- Demo: Coming soon — live demo & deployment docs in progress

---

### Infrastructure / IaC Playground (Project Placeholder 1)
- Focus: Terraform orchestration on AWS (EC2, S3, RDS).  
- Deliverables: Reproducible environment, versioned state, secure secrets handling.

(Additional project entries and case studies will be added. If you'd like walkthroughs or architectural diagrams, I can add them.)

---

## How I Work
- Developer-first: reproducible dev environments using Docker and simple scripts.
- Test & iterate: unit tests + small, isolated integration tests before deployment.
- Automate everything: CI linting, tests, builds, and promotion pipelines.
- Instrumentation: basic observability (logs + metrics) shipped with services.
- Documentation: architecture README + runbooks for deployments.

---

## DevOps Playbook — Highlights
- Containerization: Multi-stage Dockerfiles, small images, security scanning.
- CI: GitHub Actions pipelines for PR checks, build, and release workflows.
- Infra: Terraform modules for reusable infrastructure components.
- Secrets: Use managed secret stores (AWS Secrets Manager / SSM Parameter Store).
- Monitoring: Export metrics and use Prometheus & Grafana for dashboards & alerts.

---

## Project Quickstart (LogiShift) — Run locally
Clone, build, and run the main services quickly.

1) Clone repo
```bash
git clone https://github.com/yourusername/logishift.git
cd logishift
```

2) Start with Docker Compose (dev)
```bash
docker-compose up --build
# services: backend, frontend, db
```

3) Run migrations & seed data
```bash
docker exec -it logishift_backend_1 python manage.py migrate
docker exec -it logishift_backend_1 python manage.py loaddata initial_data.json
```

4) Visit
- Frontend: http://localhost:3000
- API: http://localhost:8000/api

(These commands are a sample. Exact names and scripts are in each project's README.)

---

## Open Source & Contributions
I actively maintain small utilities and contribute to student-friendly OSS projects. Contributions focus on:
- Improving developer experience (DX) via scripts and templates
- Documenting runbooks and deployment guides
- Small bugfixes and CI improvements for community repos

If you maintain a project looking for CI or infra help — I'd love to collaborate.

---

## Roadmap & Learning
Short-term learning goals:
- Deepen Kubernetes knowledge: StatefulSets, operators, and cluster autoscaling
- Advanced system design: event-driven architecture and CQRS patterns
- Observability: distributed tracing (Jaeger) and production-grade alerting

I update my roadmap in project boards and repo milestones — ping me if you want to pair on any of these topics.

---

## Contact & Availability
- LinkedIn: https://linkedin.com/in/your-profile (please replace)
- Portfolio: https://yourportfolio.com (please replace)
- Email: your.email@example.com (please replace)
- Resume: https://yourportfolio.com/resume.pdf (optional)

Open to internships and part-time contributions. If you're hiring or want to collaborate on a project, message me on LinkedIn or email me a short description.

---

## Fun Stats
<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=pkk01&show_icons=true&theme=tokyonight" alt="GitHub Stats" height="140"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pkk01&layout=compact&theme=tokyonight" alt="Top Languages" height="140"/>
</p>

---

## Want this README customized?
I can:
- Add live screenshots and architecture diagrams
- Replace placeholders (LinkedIn, portfolio, project links) with real links
- Add a resume/download button and a deployment badge for active projects
- Create a dedicated projects showcase with GIFs and walkthroughs

Tell me which additions you want (screenshots, diagrams, real links, resume, or a PR to commit this file) and I'll update it accordingly.

---

Made with ❤️ & automation — Pratham Kumar (pkk01)
