# Python for Software Engineering -- Structured Study Guide
A chapter-by-chapter study companion for the Udemy course [Python for Software Engineering Bootcamp](https://www.udemy.com/course/python-for-software-engineering/).

I started this because I was struggling with the *structure* and *why* behind the course material. Following the videos showed me what to type, but not always how the pieces fit together or why a professional would do it that way. So I'm working through the Udemy course and this guide in prallel, and turning each topic into a structured, explained, practice-ready chapter.
> **Not affiliated with Udemy or the course instructor**. This is original study material organized around the course's topics. It does not reproduce any video content, slides, or course code. If you want the course itself, you can buy it here: https://www.udemy.com/course/python-for-software-engineering/.

### How this was made (transperency)
The chapter drafts were produced with AI assistance (Claude), working from the course's published topic outline. I'm then going through each chapter alongside the Udemy lectures, running the code, correcting errors, and adding my own notes. Chapters are marked below as **Draft** until I have run every example and verified it against the course material, and **Reviewed** once I have.

### What's in here
| Chapter | Title | Maps to Udemy course? | Status |
| :--- | :--- | :--- | :--- |
| **00** | Course Overview | — | Draft |
| **01** | Python Fundamentals & Building APIs | Yes | Draft |
| **02** | Testing | Yes | Draft |
| **03** | Terminal & Remote Servers | Yes | Draft |
| **04** | Docker | Yes | Draft |
| **05** | SQL | Yes | Draft |
| **06** | Integrating Databases | Yes | Draft |
| **07** | Caching | Yes | Draft |
| **08** | Linting & Code Quality | Yes | Draft |
| **09** | GitHub & Git Workflow | Yes | Draft |
| **10** | Concurrent & Parallel Programming | Yes | Draft |
| **11** | Data Structures & Algorithms | Extra | Draft |
| **12** | Software Design & Clean Code | Extra | Draft |
| **13** | CI/CD & Deployment | Extra | Draft |
| **14** | Security Fundamentals | Extra | Draft |
| **15** | Career Prep | Extra | Draft |

Chapter 01-10 follow the same topic order as the Udemy course. Chapters 11-15 are my additions: topics I think a working engineer needs that the course doesn't cover.

### How each chapter is structured
Every chapter follows the same pattern:
1. **The concept**, explained from first principles
2. **Why it matters** in professional work
3. **Runnable examples**
4. **Common mistakes** and how to debug them
5. **Exercises** (with solutions where included)
6. **Checkpoint questions** to understanding before moving on

### The running project: Pulsecheck
The chapters build on one evolving service, a small user-and-metrics API: FastAPI + PostgreSQL + Redis, containerized with Docker, tested with pytest, linted, and deployed through a CI/CD pipeline. The code it lives in `/pulsecheck` *(added as I build it chapter by chapter)*.

### Repository layout
```
.
├── README.md
├── LICENSE
├── .gitignore
├── chapters/        # The study guide, one Markdown file per chapter
└── pulsecheck/      # The running project's code (grows as chapters are completed)
```

### How to use this alongside the Udemy course
1. Watch the Udemy lectures for a topic.
2. Read the matching chapter here to see the structure and the reasoning.
3. Type out the examples yourself (don't copy-paste) and do the exercises.
4. Answer the checkpoint questions out loud before moving on.

### Git workflow used in this repo
This repo is also practice for a professional Git workflow, so I'm using one:
- `main` always holds reviewed, working content
- One branch per chapter
- A pull request per chapter, squash-merged, linked to an issue
- Commit messages that explain what changed and why
- Tagged releases (`v0.1.0`, `v0.2.0`, ...) at milestones

See the closed pull requests and issues for the history.

### Feedback
Spotted a mistake, an unclear explanation or code that doesn't run? Please open an issue. Corrections are welcome and I'll credit them.

### License
Original content in this repository is released under the MIT License. The Udemy course and its materials belong to their respective authors.

### Author
**[Tlotlo Pilane](https://github.com/tlotlopilane)**
