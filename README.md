# Task 5 – Analytics Report & Insights Documentation

**Author:** Nandigam Praveen Kumar  
**Internship:** YuvaIntern – Data Analyst  
**Task:** 5 – Analytics Report & Insights Documentation

## Project overview

This project demonstrates how data-analysis results can be communicated through a structured report for decision-makers. It uses the UCI Student Performance dataset and presents descriptive findings, visual evidence, interpretations, limitations, and practical recommendations.

## Business / analytical objective

The objective is to examine student-performance patterns and communicate the results in a clear, stakeholder-friendly format. The analysis considers final grade (G3), study time, absences, previous academic failures, and selected student-group attributes.

## Repository structure

```text
Task_5_Analytics_Report_Insights_Documentation/
├── README.md
├── reports/
│   └── Task_5_Analytics_Report_Insights_Documentation.docx
└── analysis/
    └── supporting_student_performance_analysis.ipynb
```

## Main deliverable

- `reports/Task_5_Analytics_Report_Insights_Documentation.docx` – the Word report prepared for YuvaIntern Task 5. It includes the executive summary, analytical approach, key observations, interpretation, limitations, and recommendations.

## Supporting analysis

- `analysis/supporting_student_performance_analysis.ipynb` – the executed Jupyter notebook supporting the descriptive statistics and charts referenced in the report. Open it in Google Colab or Jupyter to inspect the code and outputs.

## Dataset

**UCI Student Performance** (dataset ID 320)  
Official source: https://archive.ics.uci.edu/dataset/320/student-performance

The dataset contains student achievement and related demographic, social, and school attributes from two Portuguese secondary schools. The notebook retrieves the dataset programmatically using `ucimlrepo`; the raw data is not duplicated in this repository.

## Key findings reported

- Mean final grade (G3) across study-time categories ranged from **10.84 to 13.23**.
- Pearson correlation between absences and G3 was **-0.091**, indicating a very weak negative linear relationship.
- Mean G3 across previous-failure categories ranged from **8.07 to 12.51**.
- Female students had a mean G3 of **12.25**; male students had a mean G3 of **11.41**.
- Students in the rural address category had a mean G3 of **11.09**; students in the urban category had a mean G3 of **12.26**.

These are descriptive observations from the dataset. They do not establish that any factor caused a change in grades and should not be generalized automatically to other student populations.

## Tools used

- Python
- Google Colab / Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn

## How to review

1. Open the Word report in the `reports/` folder.
2. Open the supporting notebook in Google Colab or Jupyter.
3. Review the code, tables, visualizations, and printed observations.
4. Compare the report's interpretations with the notebook outputs.

## Limitations

- The dataset represents students from two Portuguese secondary schools.
- The analysis is observational; associations are not proof of causation.
- Results may not represent students in other regions or education systems.
- The UCI documentation warns that earlier-period grades G1 and G2 are strongly related to final grade G3. Predictive use of these variables must account for timing and possible target leakage.

## Author

**Nandigam Praveen Kumar**  
B.Tech – Artificial Intelligence and Machine Learning
