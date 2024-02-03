# Machine Learning - COVID-19 ICU Admission Prediction

## Group 10 - Authors: Aathithyan, Greeshma, Hadia, Kaviarasi, Logan, Nikunj, Payagala, Prince, Vahin

### Executive Summary

This group project focuses on predicting Intensive Care Unit (ICU) admission for COVID-19 patients using machine learning models. Analyzing data from Hospital Sírio-Libanês in São Paulo, Brazil, we followed a four-step methodology: Exploratory Data Analysis (EDA), Data Preparation, Machine Learning Model Implementation, and AIF360 Toolkit Implementation.

#### Methodology Highlights

1. **Exploratory Data Analysis (EDA):** We conducted a comprehensive review of the dataset, identifying key characteristics and potential biases. This laid the groundwork for data preparation and model development.

2. **Data Preparation:** Employing advanced techniques, we handled missing values with a novel algorithm, addressing the non-random nature of the missing data. We balanced the target variable (ICU admission) and prepared the dataset for machine learning.

3. **Machine Learning Models:** Three models (K-Nearest Neighbors, Random Forest, Support Vector Machine) were implemented for binary classification. Random Forest emerged as the most effective model in predicting ICU admission based on health sign data.

4. **AIF360 Toolkit Implementation:** Despite dataset limitations, we explored the AIF360 Toolkit for bias detection and mitigation, focusing on gender. Careful consideration is required in applying bias mitigation tools in medical datasets where certain factors, like gender and age, play a critical role in accurate diagnosis and treatment.

#### Findings

Random Forest demonstrated superior performance in predicting ICU admission, providing valuable insights for healthcare professionals. This work aids in organizational decision-making, helping allocate resources based on COVID-19 patient health signs.

### Instructions for Running the Code

To run the code, download the Kaggle.json file from the provided link and upload it in the designated cell. Execute the code to replicate our analysis and explore further insights.

---

