# ✍️ AI Cover Letter Generator – No-Code GPT Tool

Built using:
- 🔗 Google Forms + Google Sheets
- ⚙️ Make.com (No-Code Automation)
- 🧠 OpenAI GPT-3.5 (Chat Completion API)

This tool takes resume input + job description from a form and returns a professional, tailored cover letter written by GPT, delivered via email or stored in a Google Sheet.

---

## 📌 Workflow

1. User submits:
   - Full Name
   - Resume Summary
   - Job Description
   - Tone
   - Email

2. Make.com watches for new Google Sheet rows  
3. Sends data to OpenAI API (via GPT-3.5 Turbo)  
4. GPT returns a cover letter  
5. Result is either:
   - Stored in a new column in Google Sheet, OR
   - Sent to user's email via Gmail module

---

## 💡 Prompt Used

See [`prompt.txt`](./prompt.txt)

---

## 🧪 Example Output

See [`sample-output.md`](./sample-output.md)

---

## 🧠 Tech Stack

- Make.com (Free plan)
- Google Sheets / Google Forms
- OpenAI GPT-3.5 API
- Gmail (optional)

---

## 📂 Use Cases

- Resume writers and job seekers
- Career coaches and placement cells
- AI Automation micro-services

---

## ✅ Status: Working
- Version: v1.0
- Last tested: 11th June 2025
