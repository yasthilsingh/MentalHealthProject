# 🧠 Mental Health Project – Milestone I

### University of Michigan | Master of Applied Data Science  
**Project Title:** *Stressed, Scrolling, and Sleep-Deprived: What are Teens Telling Us?*  
**Contributors:** Yasthil Singh, Howard Lin, Luca Cannis  

---

## 📌 Project Overview

This project explores how behavioral factors—specifically social media usage, sleep duration, and physical activity—relate to self-reported mental suffering in teenagers aged 13–17. Using two datasets (CDC’s YRBS survey and a Kaggle synthetic dataset), we analyzed patterns and visualized key relationships to highlight actionable insights that can inform digital wellness interventions, educational programs, and public health awareness campaigns.

---

## 🌐 Interactive Report

👉 **View our visual report here**:  
🔗 [https://mentalhealthinsights.my.canva.site](https://mentalhealthinsights.my.canva.site)

This site summarizes our research process and key findings through visual storytelling and data-driven insight.

---

## 📊 Key Research Questions

- Does frequent social media use increase the likelihood of teenagers reporting sadness or hopelessness?
- How do average sleep hours affect reported feelings of mental suffering?
- What is the relationship between physical activity and mental health?
- Is there a pattern between social media usage and sleep quality?

---

## 🧮 Datasets Used

### 1. CDC Youth Risk Behavior Surveillance System (YRBSS) – 2023
- ~19,000+ high school student responses
- Structured in fixed-width format with CDC SAS codebook
- Focused fields: `age`, `sex`, `Q80` (social media), `Q85` (sleep), `Q26` (mental suffering)

### 2. Kaggle: Mental Health Analysis Among Teenagers
- 5,000 records on stress, exercise, social media, and academic life
- Focused fields: `social_media_hours`, `sleep_hours`, `exercise_hours`, `survey_stress_score`

---

## 🧼 Data Processing Steps

We followed the **CRUD** model for transforming both datasets:

- **Create**: Standardized column names and re-coded gender/age values  
- **Read**: Parsed `.dat` files using pandas and custom SAS position-to-colspec conversion  
- **Update**: Normalized social media usage and mental suffering into binary variables  
- **Delete**: Filtered invalid rows and focused on teens aged 13–17  

Merged datasets were grouped by `age`, `sex`, and `sleep_hours` for comparative analysis.

---

## 📈 Key Findings

- 📱 **High Social Media Use ↔ Mental Distress**  
  Teens who use social media daily are far more likely to report feelings of sadness or hopelessness.

- 😴 **Sleep as a Protective Factor**  
  Teens who sleep 8+ hours per night report significantly fewer mental health struggles.

- 🏃‍♂️ **Exercise Helps, but Less Strongly**  
  Teens who exercise more report slightly lower mental suffering, especially males.

- 📊 **Sleep & Social Media Are Strongest Predictors**  
  These two behavioral indicators showed the clearest and most consistent relationships with mental health.

---

## 📎 Files in This Repository

| File | Description |
|------|-------------|
| `Notebook.ipynb` | Full Jupyter notebook with code, data cleaning, analysis, and visualizations |
| `Insights_Report.pdf` | PDF summary of project insights and graphs |
| `mentalhealthinsights.my.canva.site` | Web-based presentation with visuals and conclusions |
| `data/` | Folder containing cleaned or example data (optional for public repos) |

---

## 🛠 Tools Used

- **Python (Pandas, Matplotlib, Seaborn)** for data wrangling and visualization  
- **Jupyter Notebook** for analysis and reproducibility  
- **Canva** for storytelling and visual reporting  
- **Reveal.js (optional)** if you later want to convert your notebook to slides

---

## 🧠 Learn More

- 📄 [CDC YRBSS](https://www.cdc.gov/yrbs/data/index.html)  
- 📊 [Kaggle Mental Health Dataset](https://www.kaggle.com/datasets/aniruddhawankhede/mental-heath-analysis-among-teenagers)  
- 📚 [Pew Research: Teens and Social Media](https://www.pewresearch.org/internet/2025/04/22/teens-social-media-and-mental-health)

---

## ✨ Future Directions

- Build an interactive dashboard for public health stakeholders  
- Analyze trends across regions or school environments  
- Incorporate qualitative data (e.g., open responses, interviews) to complement quantitative findings

---

## 🔗 Contact

**Yasthil Singh**  
Master of Applied Data Science Candidate  
📬 [yasthilsingh3@gmail.com](mailto:yasthilsingh3@gmail.com)  
🌐 [LinkedIn](https://www.linkedin.com/in/yasthilsingh)

---

