# DeMaestro

**Autonomous Multi-Agent System for Full-Stack Web Application Synthesis**

Capstone Project — Software Engineering Department, Braude College of Engineering
Phase B (61999) | Project Code: 26-1-D-25

---

## About the Project

DeMaestro is a web-based system that turns a user's software idea into a running full-stack web application. The user gives their requirements as plain text or as a PDF document, and the system does the rest:

1. Reads the input and extracts structured requirements.
2. Asks the user multiple-choice questions if anything is missing.
3. Shows a Requirements Summary Document for the user to approve.
4. After approval, generates the source code for the React frontend and the FastAPI backend.
5. Tests the code inside a subprocess sandbox on the server.
6. Deploys the app to Vercel with a fresh Neon Postgres database.
7. Gives the user a live URL and a downloadable ZIP with the full source code.

The system uses two LLM providers: **Google Gemini** for analysis and requirements structuring, and **Anthropic Claude** for code writing, testing, debugging, and verification.

---

## What is Capstone A and Capstone B?

This is a two-phase academic project in the Software Engineering degree at Braude College.

**Capstone A (Phase A)** was the planning and design phase. We researched the problem, reviewed existing AI-assisted development tools, defined the functional and non-functional requirements, and designed the system architecture on paper.

**Capstone B (Phase B)** is the implementation and evaluation phase. We built the actual system, tested it end to end, and evaluated it against the requirements we defined in Phase A. This repository contains the final Phase B book and documentation.

---

## Source Code

The full source code (backend + frontend) is kept in a separate repository so this repo stays focused on the academic documentation.

**Source Code Repository:** https://github.com/owisezoubi/DeMaestro-Code

---

## Live Demo

You can try DeMaestro directly in your browser:

**Live URL:** https://de-maestro-code-53sp.vercel.app/


---

## Authors

- **Owise Zoubi** — owisezoubi@gmail.com
- **Mohamad Atamneh** — Mohamad.atamneh@e.braude.ac.il

---

## Advisor

**Dr. Natali Levi**
Senior Lecturer at Braude Academic College