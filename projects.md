---
layout: single
title: "Projects"
permalink: /projects/
---

### Agent Pairing Scheduler  
A full-stack React, Flask, and MySQL application for agent scheduling and pairing automation.  
**Tech:** React, Flask, MySQL, Docker, Python, JavaScript

**Overview:**  
Designed and implemented a custom referral and scheduling platform for the Nancy Peterson RP Group at J Barrett & Company. The system allows users to add, edit, and manage real estate agents, automatically generating pairing schedules based on agent availability and recent partner history. Ensures no two agents are paired more than once within a 6-month window and only pairs agents with overlapping availability.

**Key Features:**  
- **Automated Pairing Algorithm:** Ensures optimal, fair agent pairings with a 6-month memory and day-matching constraints.  
- **Role Management:** Intuitive CRUD interface for managing agent details and schedules.  
- **Real-time Updates:** Responsive React frontend displays pairing schedules and agent data instantly.  
- **Authentication & Security:** Supports role-based access and environment-based configuration.  
- **PDF Schedule Export:** Generates custom PDF schedules for easy distribution and record-keeping.

**Stack & Infrastructure:**  
- **Frontend:** React (JavaScript), Tailwind CSS  
- **Backend:** Flask (Python), REST API, PDF generation  
- **Database:** MySQL, SQLAlchemy ORM  
- **DevOps:** Docker support for streamlined deployment  
- **Other:** Automated testing, environment-based configuration, and extensible architecture

**Live Demo:**  
[github.com/richardpauldev/rp_scheduler](https://github.com/richardpauldev/rp_scheduler)

### Congress Sentiment Analysis  
A data science project applying NLP and visualization to historical U.S. congressional records.  
**Tech:** Python, Jupyter Notebooks, NumPy, SciPy, Hugging Face Transformers

**Overview:**  
Developed an end-to-end analysis pipeline to investigate whether sentiment in Congressional Record texts correlates with periods of heightened historical conflict (e.g., the Civil War). The project combined sentiment analysis with historical data to identify moderate correlations between legislative sentiment and national unrest.

**Key Features:**  
- **Sentiment Tracking:** Analyzes sentiment trends over time in congressional transcripts.  
- **Conflict Prediction:** Explores whether negative sentiment predicts historical conflicts.  
- **Data Visualization:** Generates comprehensive, publication-ready visualizations of sentiment trends aligned with key events.

**Stack & Infrastructure:**  
- **Analysis:** Jupyter Notebooks, Python  
- **Libraries:** NumPy, SciPy, Hugging Face Transformers  
- **Visualization:** Matplotlib, Seaborn  
- **Data:** Congressional Record (public domain, not included in repo)

**Current Status:**  
The scripts require access to a full congressional record dataset (not included in the repo). All code is functional and documented for future use.

**Live Repo:**  
[github.com/richardpauldev/congress-sentiment-analysis](https://github.com/richardpauldev/congress-sentiment-analysis)

### Security Implications of Automatic Dependency Management in Serverless Computing  
Graduate research on the risks and benefits of automated dependency tools in modern cloud environments.  
**Tech/Skills:** AWS Lambda, Azure Functions, Google Cloud Functions, Snyk, Dependabot, Security Analysis, Survey Design

**Overview:**  
Produced a comprehensive research paper for Large Scale System Security (690G, UMass Amherst) exploring how automatic dependency management tools (e.g., Snyk, Dependabot) impact the security and reliability of serverless applications across major cloud providers. The project combined literature review, hands-on evaluation, and developer surveys to assess both the strengths and pitfalls of automation in real-world serverless workflows.

**Key Contributions:**  
- **Comparative Platform Analysis:** Assessed AWS, Google Cloud, and Azure approaches to dependency management, with an emphasis on security integrations and workflow automation.
- **Developer Survey:** Designed and distributed a survey (n=14) to collect insights on practical experiences, risks, and perceived benefits of automation in serverless environments.
- **Security Findings:** Identified issues like version conflicts, hidden vulnerabilities, vendor lock-in, and transparency concerns with automated tools.
- **Best Practice Recommendations:** Proposed actionable strategies for cloud developers, including better developer education, transparency, and enhanced monitoring of automated workflows.

**Skills Demonstrated:**  
- Cloud security risk analysis  
- Survey design & data analysis  
- Comparative technical evaluation  
- Academic writing & research communication

**Artifacts:**  
- [security_report.pdf](link-to-pdf) (Final research paper, ACM format)
- [security_report.tex](link-to-tex) (LaTeX source)

**Contact:**  
richardpauldev@gmail.com
