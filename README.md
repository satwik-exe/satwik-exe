<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=gradient&customColorList=12,20,24&text=SATWIK%20MOHANTY&fontColor=ffffff&fontSize=52&fontAlignY=38&desc=Software%20Engineering%20%7C%20AI%2FML%20%7C%20Full-Stack%20Systems&descAlignY=62&descSize=18&animation=fadeIn" width="100%"/>

<a href="https://readme-typing-svg.demolab.com/">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=900&color=8B5CF6&center=true&vCenter=true&width=760&lines=Software+Engineer+in+the+Making;Building+AI-Powered+Applications;Full-Stack+%7C+Systems+%7C+AI%2FML;Turning+Complex+Problems+Into+Reliable+Systems" alt="Typing SVG"/>
</a>

<br/>

<img src="https://img.shields.io/badge/B.Tech-CSE-7C3AED?style=for-the-badge&logo=graduation-cap&logoColor=white"/>
<img src="https://img.shields.io/badge/KIIT-DU-4F46E5?style=for-the-badge&logo=google-scholar&logoColor=white"/>
<img src="https://img.shields.io/badge/CGPA-8.94%2F10-6366F1?style=for-the-badge"/>
<img src="https://img.shields.io/badge/2023--2027-1E1B4B?style=for-the-badge"/>

<br/><br/>

<img src="https://img.shields.io/badge/📍%20Odisha%2C%20India-312E81?style=flat-square"/>
<a href="mailto:satwik.mohanty01@gmail.com"><img src="https://img.shields.io/badge/Portfolio-7C3AED?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://in.linkedin.com/in/satwik-mohanty-019916281"><img src="https://img.shields.io/badge/LinkedIn-4F46E5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:satwik.mohanty01@gmail.com"><img src="https://img.shields.io/badge/Email-6366F1?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/satwik-exe"><img src="https://img.shields.io/badge/GitHub-1E1B4B?style=for-the-badge&logo=github&logoColor=white"/></a>

<br/>

<img src="https://komarev.com/ghpvc/?username=satwik-exe&label=PROFILE%20VIEWS&color=7C3AED&style=flat-square"/>
<img src="https://img.shields.io/github/followers/satwik-exe?label=FOLLOWERS&style=flat-square&color=4F46E5"/>
<img src="https://img.shields.io/github/stars/satwik-exe?label=STARS&style=flat-square&color=6366F1"/>

</div>

---

# ABOUT

I am a **final-year Computer Science & Engineering student at KIIT-DU** focused on building reliable software systems, AI-powered applications, and scalable full-stack products.

My engineering interests sit at the intersection of **software engineering, systems programming, artificial intelligence, and product engineering**. I enjoy understanding how systems work beneath the abstraction layer while also building polished applications that solve practical problems.

My experience spans **C, Java, Python, React, Node.js, FastAPI, REST APIs, Linux, Docker, MongoDB, MySQL, and LLM integrations**. I have worked on systems-level projects such as a POSIX-compatible log-structured filesystem as well as AI-enabled applications involving document processing and intelligent recommendations.

I approach product development from both an **engineering and user-impact perspective** — designing systems that are maintainable, secure, performant, and useful rather than simply functional.

### OPEN TO

`Software Engineering Internships` · `Backend Engineering` · `Full-Stack Engineering` · `AI Engineering` · `Systems Engineering` · `AI/ML Product Engineering`

---

# TECH STACK

### Languages

<p>
<img src="https://skillicons.dev/icons?i=c,java,python,javascript,css&theme=dark"/>
</p>

### Frontend

<p>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind&theme=dark"/>
</p>

### Backend & Databases

<p>
<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,flask,mongodb,mysql&theme=dark"/>
</p>

### Cloud, DevOps & Tooling

<p>
<img src="https://skillicons.dev/icons?i=git,github,linux,docker&theme=dark"/>
</p>

---

# AI / ML EXPERTISE

| Domain | Proficiency | Details |
|:---|:---:|:---|
| **LLM Integration** | `Advanced` | LLM APIs, prompt orchestration, application-level AI integration |
| **AI-Powered Applications** | `Advanced` | Building practical software products around LLM capabilities |
| **AI Agents** | `Intermediate` | Exploring agentic application architectures and tool-driven workflows |
| **Document Intelligence** | `Intermediate` | PDF extraction, structured value parsing, and intelligent interpretation |
| **Prompt Engineering** | `Intermediate` | Designing prompts for reliable application-specific outputs |
| **Python AI Stack** | `Intermediate` | Python, NumPy, Pandas and AI application development |
| **AI Product Engineering** | `Intermediate` | Integrating AI into user-facing workflows and product experiences |

---

# FEATURED PROJECTS

<details>
<summary><strong>01 · Log-Structured Filesystem — LFS-FUSE</strong></summary>

<br/>

### Systems Programming · Storage · Linux

A **POSIX-compatible log-structured filesystem** implemented in userspace using FUSE, designed around append-only storage and explicit crash-recovery mechanisms.

| Dimension | Engineering Details |
|:---|:---|
| **Stack** | `C` · `Linux` · `FUSE` · `POSIX` |
| **Scale** | `1,200+ LOC` · `1024 × 4096B disk image` |
| **Performance** | Append-only writes · Mark-compact GC · Reclaimed `85–90%` dead blocks |
| **Security** | Checksums · Sequence validation · Crash recovery |
| **Impact** | Extended file capacity `102×` using indirect block pointers |
| **Repository** | [GitHub](https://github.com/satwik-exe) |

### Engineering Highlights

- Engineered a POSIX-compatible log-structured filesystem implementing disk I/O, inode management, garbage collection, and crash recovery.
- Designed an append-only log architecture inspired by SSD/F2FS storage principles, eliminating random writes.
- Implemented mark-compact garbage collection triggered below `10%` free space.
- Reclaimed approximately `85–90%` of dead blocks while supporting log rewinding of up to `856` blocks.
- Built a three-phase crash-recovery mechanism using checksum and sequence validation.
- Implemented indirect block pointers to extend supported file size by `102×` while correctly handling GC relocation.

</details>

---

<details>
<summary><strong>02 · MediScan — Health Report Analyzer</strong></summary>

<br/>

### AI Application · Document Intelligence · Full Stack

An AI-powered web application designed to parse medical laboratory PDFs, identify abnormal values against clinical reference ranges, and provide patient-friendly explanations.

| Dimension | Engineering Details |
|:---|:---|
| **Stack** | `React` · `FastAPI` · `Python` · `pdfplumber` · `Claude API` |
| **Scale** | `25+` laboratory parameters supported |
| **Performance** | Backend PDF extraction and structured value parsing |
| **Security** | API-based architecture with isolated backend processing |
| **Impact** | Converts complex laboratory reports into accessible explanations |
| **Repository** | [GitHub](https://github.com/satwik-exe) |

### Engineering Highlights

- Building a web application for parsing medical laboratory reports and identifying abnormal measurements.
- Designed a FastAPI backend for PDF extraction, value parsing, and LLM prompt orchestration.
- Developed an LLM integration layer for generating patient-friendly explanations of flagged results.
- Built a responsive React dashboard with visual indicators across `25+` laboratory parameters.
- Structured the application around clear separation between document processing, AI orchestration, and frontend presentation.

</details>

---

<details>
<summary><strong>03 · FinSplit — Expense & Portfolio Manager</strong></summary>

<br/>

### FinTech · Full Stack · AI Product Engineering

A financial management platform designed to consolidate **expenses, investments, SIPs, liabilities, budgeting, and financial insights** into a single application.

| Dimension | Engineering Details |
|:---|:---|
| **Stack** | `React` · `Node.js` · `Express` · `MongoDB` |
| **Scale** | Multi-domain personal finance platform |
| **Performance** | Responsive dashboard with financial visualizations |
| **Security** | Authentication-focused REST API architecture |
| **Impact** | Unified expense, investment, SIP, and liability management |
| **Repository** | [GitHub](https://github.com/satwik-exe) |

### Engineering Highlights

- Developing a financial system for tracking expenses, investments, SIPs, and liabilities.
- Designing scalable REST APIs for transactions and authentication.
- Building responsive dashboards for financial visualization and analysis.
- Integrating AI-powered insights for spending analysis and budgeting recommendations.
- Designing the platform with extensibility toward broader personal-finance intelligence.

</details>

---

# EXPERIENCE

### Software Engineering / AI Engineering
**Independent Engineering Projects**

`2024 – Present`

Building and iterating on software products spanning **systems programming, full-stack development, AI integration, and financial technology**.

- Designed and implemented systems-level software using C, Linux, FUSE, and POSIX interfaces.
- Developed full-stack applications using React, Node.js, Express, FastAPI, and MongoDB.
- Integrated LLM APIs into real-world application workflows.
- Designed REST APIs for authentication, transactions, document processing, and application services.
- Built responsive frontend interfaces focused on usability and product clarity.
- Worked across the complete development lifecycle from architecture and implementation to debugging and iteration.

**Skills:** `Software Engineering` `Backend Development` `Full Stack` `AI Engineering` `Systems Programming` `REST APIs` `Linux` `Git`

---

# ACHIEVEMENTS

<div align="center">

| Recognition | Details |
|:---|:---|
| 🏆 **Google Cloud Arcade — Champion Tier** | Achieved Champion Tier in Google Cloud Arcade 2025 |
| 🌐 **Cisco Networking Academy** | Completed CCNA track covering Intro to Networks, Switching & Routing, and Enterprise Security |
| 📚 **CCNA Track** | Completed `70+ hours` of networking-focused coursework |

</div>

---

# CERTIFICATIONS

### AWS

<p>
<img src="https://img.shields.io/badge/AWS-Cloud-7C3AED?style=for-the-badge&logo=amazonaws&logoColor=white"/>
</p>

### Oracle

<p>
<img src="https://img.shields.io/badge/Oracle-Database-4F46E5?style=for-the-badge&logo=oracle&logoColor=white"/>
</p>

### NPTEL

<p>
<img src="https://img.shields.io/badge/NPTEL-Certified-6366F1?style=for-the-badge&logo=nptel&logoColor=white"/>
</p>

### Cisco

<p>
<img src="https://img.shields.io/badge/Cisco-CCNA%20Track-1E1B4B?style=for-the-badge&logo=cisco&logoColor=white"/>
</p>

---

# CODING PROFILES

<div align="center">

<a href="https://leetcode.com/">
<img src="https://img.shields.io/badge/LeetCode-Profile-7C3AED?style=for-the-badge&logo=leetcode&logoColor=white"/>
</a>

<a href="https://www.geeksforgeeks.org/">
<img src="https://img.shields.io/badge/GeeksforGeeks-Profile-4F46E5?style=for-the-badge&logo=geeksforgeeks&logoColor=white"/>
</a>

<a href="https://www.hackerrank.com/">
<img src="https://img.shields.io/badge/HackerRank-Profile-6366F1?style=for-the-badge&logo=hackerrank&logoColor=white"/>
</a>

<a href="https://www.codechef.com/">
<img src="https://img.shields.io/badge/CodeChef-Profile-312E81?style=for-the-badge&logo=codechef&logoColor=white"/>
</a>

</div>

---

# GITHUB ANALYTICS

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=satwik-exe&show_icons=true&hide_border=true&bg_color=0D1117&title_color=8B5CF6&icon_color=6366F1&text_color=C9D1D9&ring_color=7C3AED&include_all_commits=true&count_private=true" height="180"/>

<img src="https://streak-stats.demolab.com?user=satwik-exe&hide_border=true&background=0D1117&ring=7C3AED&fire=8B5CF6&currStreakLabel=8B5CF6&sideLabels=C9D1D9&dates=8B949E&currStreakNum=FFFFFF&sideNums=FFFFFF" height="180"/>

</div>

<br/>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=satwik-exe&layout=compact&hide_border=true&bg_color=0D1117&title_color=8B5CF6&text_color=C9D1D9&langs_count=10" height="180"/>

</div>

---

# GITHUB TROPHIES

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=satwik-exe&theme=discord&no-frame=true&no-bg=true&margin-w=8&column=7" width="90%"/>

</div>

---

# CONTRIBUTION ACTIVITY

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=satwik-exe&bg_color=0D1117&color=8B5CF6&line=6366F1&point=A78BFA&area=true&hide_border=true&custom_title=Contribution%20Activity" width="96%"/>

</div>

---

# CONTRIBUTION SNAKE

<div align="center">

<img src="https://raw.githubusercontent.com/satwik-exe/satwik-exe/output/github-contribution-grid-snake-dark.svg" alt="GitHub Contribution Snake"/>

</div>

---

# CURRENT FOCUS

```yaml
Learning:
  - Advanced Data Structures & Algorithms
  - Backend Engineering
  - Distributed Systems
  - AI Agents
  - LLM Application Architecture
  - System Design

Building:
  - AI-powered applications
  - Full-stack production systems
  - Financial technology products
  - Developer-focused software systems

Exploring:
  - Agentic AI
  - LLM orchestration
  - Scalable backend architectures
  - Linux internals
  - Systems programming
  - AI product engineering

Open To:
  - Software Engineering Internships
  - Backend Engineering
  - Full-Stack Engineering
  - AI Engineering
  - Systems Engineering
  - Open Source Collaboration
