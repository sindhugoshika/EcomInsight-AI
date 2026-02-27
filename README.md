# EcomInsight AI 🛒
### AI-Powered Business Intelligence Dashboard for E-Commerce

![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)
![Python](https://img.shields.io/badge/Python-3.10-blue)
![Streamlit](https://img.shields.io/badge/Built%20with-Streamlit-red)

---

## 🔴 Live Demo
👉 [Click here to open the app](#) ← replace with your Streamlit Cloud URL in Week 3 --(not done yet)

---

## 📌 What This Project Does

EcomInsight AI is a business intelligence dashboard that helps small 
e-commerce store owners understand their sales data without needing 
technical knowledge.

A store owner can:
- See which products and categories are selling best
- Track revenue trends over time
- Understand customer buying patterns
- Ask questions about their data in plain English using AI

---

## 🧠 The AI Feature

The app includes a natural language chat interface powered by OpenAI.
A user can type questions like:
- "What was my best month?"
- "Which product category brings the most revenue?"
- "How many orders were delivered late?"

The AI reads the data summary and answers in plain English.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python + Pandas | Data cleaning and analysis |
| Streamlit | Web app interface |
| Plotly | Interactive charts |
| OpenAI API | Natural language Q&A on data |
| GitHub | Version control |
| Streamlit Cloud | Free deployment |

---

## 📁 Dataset

Using the [Brazilian E-Commerce Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) from Kaggle.

Contains 100k+ real orders from 2016-2018 including:
- Orders, payments, and delivery data
- Product categories and pricing
- Customer locations across Brazil

---

## 📅 Weekly Progress Log

### ✅ Week 1 — Data Foundation
- [ ] Environment setup complete
- [ ] Dataset loaded and explored
- [ ] Data cleaned and merged
- [ ] 3 charts working in Streamlit

### 🔄 Week 2 — AI Integration  
- [ ] OpenAI API connected
- [ ] Data summary function built
- [ ] Chat feature working
- [ ] 5 additional business insights added

### ⏳ Week 3 — Polish + Deploy
- [ ] UI improved with sidebar filters
- [ ] File upload feature added
- [ ] Error handling added
- [ ] App deployed to Streamlit Cloud

---
## Project Directory Tree
ecominsight-ai/
│
├── data/
│   ├── raw/                 ← original Olist CSV files (not tracked by Git)
│   └── processed/           ← cleaned and merged data ready for analysis
│
├── notebooks/
│   └── exploration.ipynb    ← exploratory data analysis and schema documentation
│
├── src/
│   ├── clean_data.py        ← data ingestion, null handling, and preprocessing
│   ├── charts.py            ← all Plotly visualization functions
│   └── ai_chat.py           ← OpenAI API integration and natural language Q&A
│
├── app.py                   ← main Streamlit application entry point
├── requirements.txt         ← project dependencies (pip install -r requirements.txt)
├── .gitignore               ← excludes API keys, cache, and raw data from GitHub
├── .env                     ← local environment variables (not included in repo)
└── README.md                ← project overview and documentation

## 🚀 How to Run Locally
```bash
# 1. Clone the repo
git clone https://github.com/YOURUSERNAME/ecominsight-ai.git

# 2. Install dependencies
pip install -r requirements.txt

# 3. Add your OpenAI API key
# Create a .env file and add:
# OPENAI_API_KEY=your_key_here

# 4. Run the app
streamlit run app.py
```

---

## 👩‍💻 About

Built by Sindhu — MS in Computer Science, University of Arizona.
This project was built in 30 days as part of my portfolio development.

📧 your.email@gmail.com  
🔗 [LinkedIn](#) | [Upwork](#)
