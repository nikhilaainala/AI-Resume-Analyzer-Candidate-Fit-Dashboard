
# 📄 AI Resume Analyzer & Job Matching System

An **AI-powered system** that analyzes resumes, compares them with job descriptions, and generates **candidate fit insights**. It extracts skills, evaluates similarity, visualizes results with **Resume vs Job Fit Radar**, and exports recruiter-ready summaries as PDFs.

---

## 🚀 Features

* 📂 **Resume Upload** – Supports **single** or **multiple resumes** (PDF, DOCX, or ZIP).
* 📝 **Job Description Input** – Paste or upload a JD to compare.
* 🤖 **AI-Powered Matching** – Uses NLP & embeddings (Sentence Transformers) to evaluate candidate-job fit.
* 📊 **Resume vs Job Fit Radar** – Interactive radar chart comparing skills & job requirements.
* 📑 **Candidate Summary** – Generates recruiter-friendly profile summaries.
* 📥 **Export to PDF** – Save **summary, radar charts, bar charts, and recommendations**.
* 🔎 **Job Recommendations** – Suggests relevant roles based on skills & gaps.

---

## 🛠️ Tech Stack

* **Python** – Core logic & data processing
* **Streamlit** – Interactive dashboard UI
* **NLTK / Spacy** – NLP for skills extraction
* **Sentence Transformers** – Semantic similarity scoring
* **Plotly** – Resume vs Job Fit Radar + Skill Bar Charts
* **ReportLab** – PDF generation

---

## 📦 Installation

1. Clone the repo:

```bash
git clone https://github.com/your-username/ai-resume-analyzer.git
cd ai-resume-analyzer
```

2. Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the app:

```bash
streamlit run app.py
```

---



## 🎯 Example Job Description

```
We are hiring a Data Analyst with 5+ years of experience in SQL, Python, and Power BI.
The candidate should have strong skills in data visualization, statistical analysis,
and business intelligence tools.
```

---

## 📥 Export to PDF

* After analysis, click **"Generate PDF"**.
* Candidate’s **summary, Resume vs Job Fit Radar, skill bars, and job recommendations** will be saved in `outputs/` folder.



👉 Do you also want me to generate the **requirements.txt** so you can directly push it with this README?

