<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=32&pause=1000&color=6366F1&center=true&vCenter=true&width=600&height=70&lines=SmartExam+%F0%9F%93%9A;AI-Proctored+Exam+System;Next-Gen+Proctoring+%F0%9F%A4%96" alt="Typing SVG" />

# 🎓 AI-Proctored Online Exam System

[![Version](https://img.shields.io/badge/version-1.0.0-6366f1?style=flat-square&logo=git&logoColor=white)](https://github.com/singhrajvardhan/SecureExam-Platform)
[![Team](https://img.shields.io/badge/team-20_members-10b981?style=flat-square&logo=github&logoColor=white)](https://github.com/singhrajvardhan/SecureExam-Platform/graphs/contributors)
[![PRs](https://img.shields.io/badge/PRs-welcome-14b8a6?style=flat-square&logo=git&logoColor=white)](https://github.com/singhrajvardhan/SecureExam-Platform/pulls)
[![License](https://img.shields.io/badge/license-MIT-f59e0b?style=flat-square&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![PR Required](https://img.shields.io/badge/🔒_Direct_Push-BLOCKED-ef4444?style=flat-square&logo=git&logoColor=white)]()

### 🔒 No Direct Push · Pull Request Required · Code Review Mandatory

<br/>

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-https://examsystem.liveblog365.com-3b82f6?style=for-the-badge&logo=vercel&logoColor=white)](https://examsystem.liveblog365.com)
[![Documentation](https://img.shields.io/badge/📖_Documentation-Read_The_Docs-8b5cf6?style=for-the-badge&logo=readthedocs&logoColor=white)](docs/README.md)
[![Issues](https://img.shields.io/badge/🐛_Report_Issue-GitHub_Issues-ef4444?style=for-the-badge&logo=github&logoColor=white)](issues)

</div>

<br/>

## 🎯 Overview

<table>
<tr>
<td width="60%">

**SmartExam** is a cutting-edge **AI-powered online examination platform** that redefines academic integrity. Built by a dedicated team of 20 students from Cyber Security and Computer Science backgrounds, it combines intelligent proctoring with a seamless exam experience.

### Key Capabilities

| Capability | Description |
|------------|-------------|
| 🎥 **Face Detection** | Real-time identity verification and liveness detection |
| 🧠 **Behavior Analysis** | AI monitors head movements, eye gaze, and suspicious patterns |
| 🚫 **Tab Switching** | Instant detection of navigation away from exam window |
| 📸 **Periodic Snapshots** | Random captures to ensure candidate presence |

</td>
<td width="40%" align="center">

```mermaid
graph TD
    A[Student Starts Exam] --> B[Face Verification]
    B --> C{Valid Face?}
    C -->|Yes| D[Exam Begins]
    C -->|No| E[Access Denied]
    D --> F[AI Proctoring]
    F --> G{Suspicious Activity?}
    G -->|Yes| H[Alert Proctor]
    G -->|No| I[Continue Exam]
