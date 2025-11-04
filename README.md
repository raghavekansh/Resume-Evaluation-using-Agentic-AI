# 🤖 Resume Evaluation System using Agentic AI 

### 🧩 Project Overview
This project showcases an **Agentic AI-powered Resume Evaluation System** built on **n8n** and **Google Gemini models**.  
It automates the **end-to-end HR screening workflow** — from form submission, resume text extraction, candidate summarization, AI-based evaluation, to structured feedback and HR reporting.

### ⚙️ Workflow Overview
- Built in **n8n** as a 17-node workflow integrating PDF extraction, LangChain, Gemini API, and Gmail automations.  
- **Input:** PDF Resume uploaded via Candidate Form  
- **Process:**  
  - Extract text  
  - Parse education, job history, skills, and personal info  
  - Summarize and evaluate profile with Gemini  
  - Append structured results to Google Sheets  
  - Send formatted HR summary and candidate acknowledgment emails  
- **Output:** Automated resume report (Google Sheets + HR email summary)

---



## 🚀 Key Highlights
- Designed an **Agentic AI pipeline** capable of autonomously analyzing and evaluating resumes against job roles.  
- Used **n8n orchestration** to connect Gmail, Google Sheets, PDF parsing, and Gemini AI for LLM-based scoring.  
- Built modular **information extraction**, **summarization**, and **evaluation** chains using LangChain-style logic.  
- Integrated **structured output parsing** to produce consistent JSON responses for HR systems.  
- Enabled automatic **email confirmations**, **HR summary generation**, and **error monitoring** with fallback alerts.  
- Demonstrates an **AI-first, modular, and reusable workflow** — a real-world example of enterprise automation.

---

### 🧱 Technologies and Frameworks
- **n8n** (Agentic Workflow Automation)
- **LangChain**
- **Google Gemini (LLM)**
- **FastAPI & Python**
- **Google Sheets API**, **Gmail API**






