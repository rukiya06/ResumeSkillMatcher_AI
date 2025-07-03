💼 Resume Skill Matcher + AI Feedback Generator 🤖

A GenAI-based project that evaluates a resume against a target job role and provides:
- ✅ Matched skills
- ❌ Missing skills
- 💬 Actionable suggestions
- 🔐 Match Score (trust level)

This tool helps job seekers identify gaps in their resume and optimize it for specific roles using AI-powered matching.

---

## 🚀 Features

- 📄 Upload a resume PDF
- 🧠 Extract skills using simple NLP and semantic logic
- 🎯 Compare with a predefined skill list for a specific job (e.g., Data Engineer)
- 🔐 Calculate Match Score (% of required skills found)
- 💬 Generate smart improvement tips

---

## 🛠️ Tech Stack

- Python
- PyMuPDF – PDF parsing
- Regular Expressions – Skill detection
- sentence-transformers – (Optional for semantic matching)
- FAISS (optional for future similarity improvements)

---

## 💻 How It Works

1. **Upload Resume**  
   → Extract text using `PyMuPDF`

2. **Define Job Role**  
   → Example: `"Data Engineer"` with a list of required skills

3. **Extract Resume Skills**  
   → Match exact or fuzzy keywords

4. **Compare Skills**  
   → Show which skills are found or missing

5. **Generate Suggestions**  
   → Recommend what to add to improve matching

---

## 🧠 What You'll Learn

- How to use AI to analyze unstructured documents
- How to match resume content with job expectations
- How to provide actionable, customized career guidance
- How to build a real-world GenAI application using basic tools


