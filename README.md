# US Health Insurance Dataset Analysis

## Overview

This repository contains an analysis of the US Health Insurance dataset, exploring various aspects of the data, conducting hypothesis testing, and building predictive models using machine learning techniques.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset Information](#dataset-information)
3. [Tasks](#tasks)
4. [Directory Structure](#directory-structure)
5. [Usage](#usage)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

Health insurance is a critical aspect of healthcare in the United States, and this dataset provides insights into the factors influencing insurance charges. The analysis covers exploratory data analysis (EDA), hypothesis testing, and predictive modeling using linear regression.

## Dataset Information

- The dataset contains information on insured individuals, including attributes such as Age, Sex, BMI, Number of Children, Smoking status, Region, and Insurance Charges.
- There are no missing or undefined values in the dataset.

## Tasks

The tasks performed in this analysis include:

- Exploratory Data Analysis (EDA)
  - Univariate analysis
  - Hypothesis testing (Two Sample t Test, ANOVA, Correlation Analysis)
  - Bivariate and Multivariate analysis

- Modeling
  - Linear Regression
    - User-defined function for encoding
    - Train-test split
    - Pipeline for preprocessing
    - Model evaluation on both training and test data
  - Polynomial Regression
    - Model evaluation on both training and test data
  - Overcoming overfitting with Lasso and Ridge regression

## Directory Structure

- `data/`: Contains the US Health Insurance dataset.
- `notebooks/`: Jupyter notebooks for the analysis.
- `results/`: Saved results, models, and evaluation metrics.
- `scripts/`: Helper scripts or functions used in the analysis.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/us-health-insurance.git
   cd us-health-insurance
