****COVID-19 India Data Analysis (Pandas Project)****


**Project Overview**

-This project performs an end-to-end exploratory data analysis (EDA) on official Government of India COVID-19 datasets.

-The analysis focuses on time-based trends, state-wise insights, and policy-relevant KPIs using Python, Pandas, and NumPy.

-This project is designed to demonstrate real-world data analyst skills, including data cleaning, aggregation, KPI creation, and structured output generation.


***Objectives***

--Clean and standardize raw government COVID-19 data

--Handle missing values and inconsistent column naming

--Perform daily and monthly time-series analysis

--Conduct state-wise comparison for cases, testing, and vaccination

--Create advanced KPIs for decision-making

--Export business-ready CSV files


**Dataset Sources**

Official Government of India datasets:

1.COVID-19 Case Data – covid_19_india.csv

2.Statewise Testing Data – StatewiseTestingDetails.csv

3.Statewise Vaccination Data – covid_vaccine_statewise.csv


**Tools & Technologies**

---Python

---Pandas

---NumPy

---Jupyter Notebook

---Git & GitHub


**Project Structure**

covid-19-india-data-analysis/

├── data/

│   ├── raw/              # Original government datasets

│   └── cleaned/          # Cleaned & standardized datasets
│
├── notebooks/
│   └── covid_india_data_analysis.ipynb
│
├── outputs/
│   ├── time_analysis/    # Daily & monthly trends
│   ├── state_analysis/   # State-wise summaries
│   └── kpis/             # Business & policy KPIs
│
└── README.md


**Analysis Performed**

 1.Data Cleaning
 
 2.Standardized date formats
 
 3.Resolved state naming inconsistencies
 
 4.Filled missing values with appropriate defaults (NaN / 0)
 
 5.Created cleaned datasets for reproducibility


**Time-Based Analysis**

Daily confirmed, deaths, and recovered trends

Monthly cases trend

Monthly testing trend

Monthly vaccination trend


**Output files:**

daily_cases_trend.csv

monthly_cases_trend.csv

monthly_testing_trend.csv

monthly_vaccination_trend.csv


**State-Wise Analysis**

Total confirmed, deaths, recovered per state

State-wise testing summary

State-wise vaccination summary

Top 10 states by confirmed cases


**Output files:**

statewise_total_cases.csv

statewise_testing_summary.csv

statewise_vaccination_summary.csv

top_10_states_cases.csv


**Advanced KPIs**
Total confirmed cases

Mortality rate

Recovery rate

Test positivity rate

Vaccination coverage


**Output files:**

overall_kpis.csv

statewise_kpis.csv

testing_positivity_rate.csv

vaccination_coverage.csv


***Key Insights***
--Identified states with highest COVID-19 burden

--Evaluated testing efficiency using positivity rates

--Analyzed vaccination rollout across states

--Produced reusable, business-friendly datasets


***Outcomes***

-Cleaned and standardized datasets

-Reproducible Jupyter Notebook analysis

-Structured CSV outputs for stakeholders

-GitHub-ready data analytics project





