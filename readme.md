# Homework 10

This project showcases an automated CI/CD pipeline using GitHub Actions. It includes test execution, Docker image building, and image deployment to Docker Hub.

---

## ✅ GitHub Actions Status

The CI pipeline triggered on every push to the `main` branch includes two jobs:
- `test (Python 3.10.12)`
- `build-and-push-docker`

🟢 All jobs completed successfully.  
⏱ Total duration: **4m 31s**  
🔗 [View GitHub Actions Run] https://github.com/psbpras/homework-10/actions/runs/14648945475

---

## 🐳 Docker Hub Image

The Docker image was built and successfully pushed to Docker Hub.

- Repository:
- <img width="931" alt="{E458BE8A-C101-46C3-8B11-BB4693A9998E}" src="https://github.com/user-attachments/assets/856a09d8-a353-43e9-836e-277c73b35ea9" />



---

## 🧪 Testing and Coverage

Test suite executed using `pytest`, with an overall test coverage of **90%**.

---

## 🛠️ Closed Issues and Fixes

- **[passwords]https://github.com/psbpras/homework-10/tree/passwords**  
  Fixed bugs related to password validation and hashing.

- **[email]https://github.com/psbpras/homework-10/tree/email**  
  Resolved email validation issues and standardized email input formats.

- **[username] https://github.com/psbpras/homework-10/tree/username**  
  Implemented checks for duplicate usernames and format restrictions.

- **[profile-pic]https://github.com/psbpras/homework-10/tree/profile-pic**  
  Fixed image upload validation and format support.

- **[1_Mismatch data]https://github.com/psbpras/homework-10/tree/1_mismatch-data**  
  Fixed inconsistent data formatting between API and frontend.

---

## 🔁 Pull Requests

All above issues were resolved through dedicated pull requests with linked commits, followed by successful CI runs and Docker builds.

---

## ⚙️ Tools & Tech

- **Python 3.10.12**
- **Pytest**
- **Docker**
- **GitHub Actions**

---

## Summary 

Over the course of this project, I got hands-on experience with software version control by actively managing a Git repository. I used pull requests (PRs) not just to track changes, but also to maintain clean, reviewable code and ensure that every update was tested before merging into the main branch. Along the way, I also gained a stronger understanding of RESTful API integration, enabling smooth communication between different services in the system.

One of the biggest takeaways was setting up and improving automated CI/CD pipelines. Every push triggered builds and unit tests automatically, and once everything passed, the app was packaged into a Docker container and pushed straight to Docker Hub. This streamlined the entire development-to-deployment cycle and showed me how real-world applications can scale more efficiently with containerization and automation in place.

