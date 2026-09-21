# Salary Prediction using Simple Linear Regression

A end-to-end Machine Learning pipeline that predicts an employee's salary based on their years of experience using Simple Linear Regression.

---

## Project Overview

This project implements a fundamental supervised machine learning model to estimate salary growth relative to professional experience. The dataset contains empirical observations mapping years of experience to annual compensation.

### Key Objectives
* Conduct Exploratory Data Analysis (EDA) and data cleansing.
* Perform feature and target extraction (vertical dataset splitting).
* Train a Simple Linear Regression model using `scikit-learn`.
* Evaluate model parameters and feature relationships.

---

## Dataset Description

The dataset `Salary_dataset.csv` contains 30 samples with the following schema:

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| `Unnamed: 0` | Integer | Index column (removed during preprocessing) |
| `YearsExperience` | Float | Total years of professional experience (Feature / $X$) |
| `Salary` | Float | Annual salary in USD (Target / $y$) |

---

## Machine Learning Pipeline
