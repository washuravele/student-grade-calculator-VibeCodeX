# Student Grade Calculator – DevOps CI/CD Project

## Project Overview

The Student Grade Calculator is a Java web application developed for the ASSDX4A DevOps Practical Assessment. The application calculates student final marks using semester marks and examination marks according to VUT grading policies.

This project demonstrates the implementation of modern DevOps practices including:
- GitHub version control
- Feature branching and pull requests
- Automated testing using JUnit and Maven
- Continuous Integration using GitHub Actions and Jenkins
- Docker containerisation
- Cloud deployment using Render.com

---

# Technologies Used

- Java
- Maven
- JUnit
- Git & GitHub
- GitHub Actions
- Jenkins
- Docker
- Apache Tomcat
- Render.com

---

# Application Features

- Final mark calculation
- Grade determination
- Exam admission validation
- Class average calculation
- Pass rate calculation
- Highest mark identification
- Supplementary eligibility checking
- Student report generation

---

# Grading Rules

| Final Mark Range | Grade |
|---|---|
| 80 – 100 | Distinction |
| 70 – 79 | Merit |
| 60 – 69 | Credit |
| 50 – 59 | Pass |
| 0 – 49 | Fail |

## Final Mark Formula
```
Final Mark = (Semester Mark × 0.4) + (Exam Mark × 0.6)
A student requires a semester mark of at least 40 to qualify for exam admission.
```
---

# GitHub Collaboration Workflow

The project used feature branches to support collaboration between group members.

| Team Role | Branch |
|---|---|
| Documentation | feature/documentation |
| Testing | feature/testing |
| Bug Fixing | feature/bug-fixes |
| CI Pipeline | feature/ci-pipeline |
| Deployment | feature/docker-deploy |

Each member worked independently on their assigned branch and merged changes into the `main` branch using pull requests.

---

# Continuous Integration

GitHub Actions was configured to:
- automatically build the project
- run unit tests
- detect build failures
- support Continuous Integration workflows

The CI pipeline executes whenever code is pushed to the repository or when pull requests are created.

---

# Docker Containerisation

The application was containerised using Docker and deployed on Apache Tomcat.

## Build Docker Image

```bash
docker build -t student-grade-calculator .
```

## Run Docker Container

```bash
docker run -p 8080:8080 student-grade-calculator
```

---

# Deployment

The application was deployed online using Render.com through automated deployment workflows connected to GitHub Actions.

[Live URL](https://student-grade-calculator-vibecodex.onrender.com)

---

# Contributors

| Surname and Initials | Student Number | Role
|---|---|---|
| Ravele W|223019267 | Group Leader |
| Shaun S |223430145 | CI Engineer |
| Motlatso M |224062565| Deployment Lead |
| Phalane RM |222476400      | Bug Fix Engineer |
| Tshidiso T | 22379250   | QA/Tester |

---









