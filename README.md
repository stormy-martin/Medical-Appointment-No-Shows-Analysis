# Medical Appointment No-Shows Analysis

## Overview
This project analyzes a dataset of 110,526 medical appointments in Brazil to identify
factors that predict whether a patient will show up for their scheduled appointment.
Understanding no-show patterns can help healthcare providers reduce missed appointments
and improve resource allocation.

## Key Questions
- Does receiving an SMS reminder reduce appointment no-shows?
- Does a patient's age affect whether they show up?
- Do patients with chronic conditions (hypertension or diabetes) show up more reliably?

## Key Findings
- Patients who received SMS reminders had a **higher** no-show rate (27.6%) than
  those who did not (16.7%) — an unexpected finding that warrants further investigation
- Younger patients (ages 19–35) had the highest no-show rate (23.8%), while patients
  aged 56+ were the most reliable (15.6%)
- Patients with chronic conditions showed better attendance — hypertension patients
  (17.3%) and diabetic patients (18.0%) both had lower no-show rates than healthier patients

## Methods
- Exploratory data analysis and descriptive statistics
- Data cleaning and wrangling (handling invalid values, column drops, binary encoding)
- Univariate and bivariate visualizations
- Group-based comparison analysis

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Dataset
- **Source:** [Kaggle - No-show Appointments](https://www.kaggle.com/joniarroba/noshowappointments)
- **Records:** 110,527 medical appointments
- **Location:** Brazil, 2016
- **Key columns:** Age, Gender, SMS_received, Hipertension, Diabetes, No-show

## Limitations
- Findings reflect correlations only — causation cannot be established
- Dataset is limited to Brazil in 2016 and may not generalize to other settings
- Wait time between scheduling and appointment was not available in the dataset
  and may explain some observed patterns
