# BrainStation Data Science Final Project - GlassDoor Salary Data Analysis

In this project I go through the data trends of the glassdoor tech jobs dataset I found on kaggle. My purpose is to identify the highest paying skill as a data scientist of the listed skills, like Python, R, spark, AWS and excel.
Link - https://www.kaggle.com/datasets/thedevastator/jobs-dataset-from-glassdoor/data

### About the Data

This dataset contains job postings from Glassdoor.com from 2017 with the following features It can be used to analyze the current trends based on job positions, company size, etc.

#### Data Columns

##### File: eda_data.csv and salary_data_cleaned.csv

| Column name | Description                                                                                          |
| ----------- | ---------------------------------------------------------------------------------------------------- |
| job_state   | The state where the job is located (String)                                                          |
| same_state  | A binary indicator of whether the job is in the same state as the person looking at the job (String) |
| age         | The age of the person looking at the job (Numeric)                                                   |
| python_yn   | A binary indicator of whether the person looking at the job knows Python (String)                    |
| R_yn        | A binary indicator of whether the person looking at the job knows R (String)                         |
| spark       | A binary indicator of whether the person looking at the job knows Spark (String)                     |
| aws         | A binary indicator of whether the person looking at the job knows AWS (String)                       |
| excel       | A binary indicator of whether the person looking at the job knows Excel (String)                     |

##### File: glassdoor_jobs.csv

| Column name | Description                                         |
| ----------- | --------------------------------------------------- |
| job_id      | The unique identifier for the job posting (Numeric) |
