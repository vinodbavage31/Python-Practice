<div align="center">

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python Logo" width="100" height="100"/>

# 🐍 Python Practice Hub

**A structured, community-driven repository to master Python — from absolute beginner to interview-ready.**

[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge)](LICENSE)
[![Open Source](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-red?style=for-the-badge)](https://github.com/vinodbavage31/Python-Practice)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)](CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/vinodbavage31/Python-Practice?style=for-the-badge&color=yellow)](https://github.com/vinodbavage31/Python-Practice/stargazers)

<br/>

> *"Practice is the hardest part of learning, and training is the essence of transformation."*
> — Ann Voskamp

**[ Browse Topics](#-folder-structure) · [Get Started](#-getting-started) · [Contribute](#-contributing) · [Discuss](https://github.com/vinodbavage31/Python-Practice/discussions)**

</div>

---

## About This Repository

**Python Practice Hub** is a free, open-source collection of structured practice problems, mini-projects, and notes covering the full Python learning journey — from environment setup all the way to interview preparation and real-world libraries.

Whether you're just starting out or sharpening your skills for a technical interview, this repo gives you a clear, topic-by-topic roadmap with hands-on exercises to build real understanding.

### ✨ What Makes This Different?

| Feature | Description |
|---|---|
| **Structured Curriculum** | 15 topic folders following a logical learning progression |
|  **Practice-First** | Every concept paired with exercises you can run immediately |
| **Real Projects** | Applied mini-projects to cement your knowledge |
| **Interview Ready** | Dedicated section for common Python interview questions |
| **Community Driven** | Open-source and welcomes contributions from all skill levels |

---

## 📁 Folder Structure

```
Python-Practice/
│
├── 📁 00_setup/                   # Environment setup, pip, virtual environments
├── 📁 01_python_basics/           # Variables, data types, operators, input/output
├── 📁 02_control_flow/            # if/else, loops, break, continue, pass
├── 📁 03_data_structures/         # Lists, tuples, sets, dictionaries
├── 📁 04_functions/               # Functions, args/kwargs, lambda, recursion
├── 📁 05_strings/                 # String methods, formatting, slicing, regex
├── 📁 06_file_handling/           # Reading/writing files, CSV, JSON, paths
├── 📁 07_error_handling/          # try/except, custom exceptions, logging
├── 📁 08_oop/                     # Classes, inheritance, polymorphism, magic methods
├── 📁 09_modules_packages/        # Imports, creating packages, __init__.py
├── 📁 10_standard_library/        # os, sys, datetime, collections, itertools, etc.
├── 📁 11_algorithms_practice/     # Sorting, searching, recursion, complexity
├── 📁 12_libraries/               # NumPy, Pandas, Matplotlib, Requests, etc.
├── 📁 13_projects/                # End-to-end mini projects
├── 📁 14_interview_practice/      # Common Python interview Q&A and challenges
│
├── 📁 datasets/                   # Sample datasets for practice exercises
├── 📁 notes/                      # Concept notes, cheat sheets, references
│
└── 📄 README.md
```

---

## 🗺️ Learning Roadmap

```
[ Beginner ]──────────────────────────────────────────────────── [ Advanced ]

  00_setup → 01_basics → 02_control_flow → 03_data_structures
                                                      ↓
  08_oop ← 07_error_handling ← 06_file_handling ← 04_functions
    ↓
  09_modules → 10_standard_library → 11_algorithms → 12_libraries
                                                          ↓
                                          13_projects → 14_interview_practice
```

>  **Tip:** Follow the numbered folders in order if you're a beginner. If you're intermediate, jump to any topic you need to reinforce.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Python 3.8+](https://www.python.org/downloads/)
- [Git](https://git-scm.com/downloads)
- A code editor — [VS Code](https://code.visualstudio.com/) is recommended

Verify your installation:

```bash
python --version   # Should show Python 3.8 or higher
git --version      # Should show git version
```

---

### Cloning the Repository

**Option 1 — Clone via HTTPS (recommended for beginners)**

```bash
git clone https://github.com/vinodbavage31/Python-Practice.git
cd Python-Practice
```

**Option 2 — Clone via SSH (recommended if you have SSH keys set up)**

```bash
git clone git@github.com:vinodbavage31/Python-Practice.git
cd Python-Practice
```

**Option 3 — GitHub CLI**

```bash
gh repo clone vinodbavage31/Python-Practice
cd Python-Practice
```

---

### 🛠️ Setting Up a Virtual Environment

It's best practice to use a virtual environment to keep your dependencies isolated.

```bash
# Create a virtual environment
python -m venv venv

# Activate it
# On macOS/Linux:
source venv/bin/activate

# On Windows (Command Prompt):
venv\Scripts\activate

# On Windows (PowerShell):
venv\Scripts\Activate.ps1

# Install dependencies (if any)
pip install -r requirements.txt
```

---

###  Running Practice Files

Navigate into any topic folder and run the Python files:

```bash
cd 01_python_basics
python variables.py
```

Or run from the root:

```bash
python 01_python_basics/variables.py
```

---

## 🤝 Contributing

We ❤️ contributions! Whether it's fixing a typo, adding a new practice problem, or improving an explanation — every contribution counts.

### How to Contribute

#### Step 1 — Fork the Repository

Click the **Fork** button at the top right of this page to create your own copy.

#### Step 2 — Clone Your Fork

```bash
git clone https://github.com/<your-username>/Python-Practice.git
cd Python-Practice
```

#### Step 3 — Create a New Branch

Always create a new branch for your changes. Never commit directly to `main`.

```bash
# General format
git checkout -b <type>/<short-description>

# Examples
git checkout -b feature/add-regex-exercises
git checkout -b fix/typo-in-oop-notes
git checkout -b docs/update-readme
```

#### Step 4 — Make Your Changes

Add your practice questions, fix a bug, or improve documentation. Follow the existing folder structure and naming conventions.

```
📌 Naming Conventions:
  - Python files:   snake_case.py           → oop_inheritance.py
  - Folders:        numbered_snake_case/    → 08_oop/
  - Notes/Docs:     descriptive names       → string_methods_cheatsheet.md
```

#### Step 5 — Stage and Commit

Write clear, descriptive commit messages:

```bash
git add .
git commit -m "feat: add list comprehension exercises to 03_data_structures"
```

**Commit Message Convention:**

| Prefix | Use For |
|--------|---------|
| `feat:` | Adding new exercises or content |
| `fix:` | Fixing bugs or incorrect code |
| `docs:` | README or notes updates |
| `refactor:` | Improving existing code without changing behavior |
| `style:` | Formatting, whitespace |

#### Step 6 — Push Your Branch

```bash
git push origin feature/add-regex-exercises
```

#### Step 7 — Open a Pull Request

1. Go to your fork on GitHub
2. Click **"Compare & pull request"**
3. Fill in the PR title and description clearly
4. Click **"Create pull request"**

A maintainer will review your PR and either merge it or leave feedback. 🎉

---

### 🔄 Keeping Your Fork in Sync

If you forked this repo earlier, here's how to keep it up to date with the original:

```bash
# Step 1: Add the original repo as "upstream" (only once)
git remote add upstream https://github.com/vinodbavage31/Python-Practice.git

# Step 2: Fetch the latest changes from upstream
git fetch upstream

# Step 3: Merge upstream changes into your local main branch
git checkout main
git merge upstream/main

# Step 4: Push the updated main to your fork
git push origin main
```

---

### ✅ Contribution Guidelines

Please follow these guidelines to keep the repo clean and consistent:

- [ ] Each file should be **self-contained** and runnable
- [ ] Add **comments** to explain your code — this is a learning repo
- [ ] Include **example outputs** in comments where helpful
- [ ] Don't add solved answers directly inside exercise files — keep problems and solutions separate
- [ ] Test your code before submitting a PR
- [ ] Be respectful and kind in code reviews and discussions

---

## 📋 Contribution Ideas

Not sure where to start? Here are some ideas:

- ✏️ Add new practice questions to any topic folder
- 🐛 Fix incorrect code or broken examples
- 📝 Write notes or cheat sheets for the `notes/` folder
- 🧩 Add a new mini-project to `13_projects/`
- 💬 Add real interview questions to `14_interview_practice/`
- 🌐 Translate notes to other languages
- 🔗 Add references or resource links to topic folders

---

## 📜 License

This project is licensed under the **MIT License** — free to use, modify, and distribute with attribution.

```
MIT License

Copyright (c) 2026 Vinod Bavage

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

See the full [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgements

- All contributors who add practice questions and improvements
- The open-source Python community
- [Python.org](https://docs.python.org/3/) for official documentation

---

## 👤 Author & Maintainer

<div align="center">

**Vinod Bavage**

[![GitHub](https://img.shields.io/badge/GitHub-vinodbavage31-181717?style=for-the-badge&logo=github)](https://github.com/vinodbavage31)

*Built with ❤️ for the Python learning community*

</div>

---

<div align="center">

⭐ **If this repo helped you, please give it a star — it helps others find it too!** ⭐

</div>