# Teaching Analytics: Does Curriculum Match Industry Skills?

*A Text Mining Approach to Curriculum–Industry Alignment*

## Team Members

* Abby Peck
* Emily Caraher
* Nandini Anand Kumar
* Riju Hariharan
* Sarvesh Miskin
* Varsha Ramesh

---

## Project Overview

This project evaluates whether **top global MSBA programs** teach the skills that employers currently demand.
Using text mining, topic modeling, and cosine similarity, the team analyzed:

* Curriculum descriptions from leading MSBA programs
* Job postings from Indeed (Data Analyst, Business Analyst, Data Scientist roles)

The workflow quantifies alignment, identifies curriculum gaps, highlights market demand trends, and compares U.S. vs. non-U.S. programs.

---

## Objectives

* Extract skills taught across MSBA curricula
* Compare curriculum content with job role skill requirements
* Quantify alignment using cosine similarity
* Identify gaps between academic programs and market needs
* Analyze differences between U.S. and global MSBA programs

---

## Workflow

Based on the 6-step evaluation flow diagram (PDF page 3) 

| Stage                        | Description                                                     |
| ---------------------------- | --------------------------------------------------------------- |
| **Data Collection**          | Scraped MSBA curriculum webpages + Indeed job postings          |
| **Data Cleaning**            | Lowercasing, stopword removal, stemming, tokenization           |
| **Skill Extraction**         | Extracted skill keywords using CounterVectorizer                |
| **Cosine Similarity**        | Compared curriculum vectors with job role skill vectors         |
| **Topic Modeling**           | Applied LDA to identify dominant curriculum themes              |
| **Analysis & Visualization** | Charted alignment scores, topic distributions, and ROI insights |

---

## Dataset Scope

### **Universities Analyzed**

**Top U.S. MSBA Programs**

* Carnegie Mellon University
* MIT
* NYU
* Columbia University
* UT Austin

**Ranked 5–10 U.S. MSBA Programs**

* USC
* University of Washington
* Purdue
* Georgetown
* University of Minnesota

**Top Non-U.S. Programs**

* London Business School
* Imperial College
* Warwick
* NUS (Singapore)
* Melbourne Business School

### **Job Listings**

* Source: **Indeed US**
* Roles:

  * Business Analyst
  * Data Analyst
  * Data Scientist
* Timeframe: October 2025

---

## 🧪 Skill Detection

**Job Role–Specific Skills Identified**

* *Data Analyst*: SQL, Python, Excel, Power BI, Tableau
* *Business Analyst*: SQL, Excel, dashboards, Power BI
* *Data Scientist*: Python, Machine Learning, R, Optimization, SQL

**Curriculum-Derived Skills**
Python, SQL, R, statistics, regression, optimization, ML, visualization, causal inference

---

## Key Findings

### 1. Alignment Metrics (Top 5 Universities)

* CMU and NYU showed higher curriculum–industry alignment
* MIT had lower alignment due to **fewer skills listed publicly** (page 7)

### 2. Market Demand vs Curriculum Supply

* U.S. schools generally align better than Non-U.S. schools for U.S. job roles
* Carnegie Mellon had the strongest alignment across DS/DA/BA roles

### 3. Topic Modeling Insights

* Programs cluster around similar themes (ML, stats, data engineering)
* Variation arises mainly in business domain depth & advanced ML topics

### 4. ROI Analysis

* Some programs deliver higher ROI based on salary uplift vs tuition
* Non-U.S. schools show competitive ROI despite lower alignment

---

## Conclusion

* Top 5 U.S. MSBA programs generally align best with U.S. job market needs
* Some perceived “misalignment” is due to **incomplete curriculum documentation** on program websites
* Non-U.S. programs vary widely in U.S. market readiness
* Curriculum transparency plays a major role (MIT example)

---

## Project Files

| Resource                              | Link                         |
| ------------------------------------- | ---------------------------- |
| **Project Presentation**              | *(insert PDF/PPT link here)* |
| **Full Codebase (Jupyter Notebooks)** | *(insert GitHub link here)*  |
| **Data Collection Notebook**          | *(placeholder)*              |
| **Skill Extraction Notebook**         | *(placeholder)*              |
| **Topic Modeling Notebook**           | *(placeholder)*              |
| **Visualization / Report Notebook**   | *(placeholder)*              |
