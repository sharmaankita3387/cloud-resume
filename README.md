# Cloud Engineering Portfolio Resume (Phase 1)

## Project Overview
Welcome to the repository for my cloud-optimized portfolio resume website. This project marks Phase 1 of my transition into Cloud Engineering and serves as the baseline for my **Cloud Resume Challenge** journey. 

Before deploying to production cloud environments, this phase establishes a clean, semantic web frontend built completely from scratch to ensure a strong grasp of web architecture fundamentals.

---

## Project Objectives & Roadmap
*   **Semantic Structure:** Implement clean, accessible HTML5 templates to structure technical resume data.
*   **Responsive Styling:** Leverage CSS3 (including modern Flexbox layouts) to build a clean, professional, and scannable UI.
*   **Version Control & CI/CD Baseline:** Establish git-based workflows and remote tracking on GitHub to prep for future deployment automation.
*   **Architectural Progression:** Lay the groundwork for mapping static assets to decentralized cloud infrastructure.

---

## Tech Stack & Tools
*   **Frontend:** HTML5, CSS3 (Flexbox architecture)
*   **Version Control:** Git, GitHub
*   **Environment:** Visual Studio Code

---

## Key Engineering Takeaways
Through this foundational iteration, I developed core competencies in:
*   **Document Object Model (DOM) Architecture:** Structuring data logically using semantic tags (`<header>`, `<section>`, `<ul>`) for better accessibility and screen-reader indexing.
*   **Layout Mechanics:** Utilizing modern CSS properties (`display: flex`, `justify-content: space-between`) to handle dynamic element alignment across viewport sizes without relying on heavy frameworks.
*   **Git Gitflow Basics:** Managing local-to-remote code deployment pipelines via the CLI.

---

## Future Architecture Roadmap (The Cloud Resume Challenge)
This repository is designed to evolve. The next phases of this project will involve migrating this static site into a fully serverless cloud infrastructure on AWS:

1.  **Storage & Distribution:** Host static assets securely on an **AWS S3** bucket and configure **Amazon CloudFront** as a global Content Delivery Network (CDN) with an SSL/TLS certificate via **AWS Certificate Manager (ACM)**.
2.  **DNS Management:** Route a custom domain name using **Amazon Route 53**.
3.  **Serverless Backend:** Build a dynamic visitor counter using an **AWS Lambda** function written in Python, triggered via **Amazon API Gateway**, and persisting state in an **Amazon DynamoDB** NoSQL database.
4.  **CI/CD Pipeline:** Automate testing and deployment using **GitHub Actions** so that every `git push` automatically updates the live AWS cloud infrastructure.

---

## Author
**Ankita Sharma**  
*Software Engineering Co-op Student at McMaster University* | *Aspiring Cloud Engineer*  
*   **LinkedIn:** [linkedin.com/in/sharmaankita3387](https://linkedin.com/in/sharmaankita3387)
*   **GitHub:** [github.com/sharmaankita3387](https://github.com/sharmaankita3387)
