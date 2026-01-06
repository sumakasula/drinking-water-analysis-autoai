# Improved Source of Drinking Water Analysis using IBM Watson AutoAI

## Project Overview
Access to safe and improved drinking water remains a critical challenge in India, particularly in rural and underdeveloped regions. Despite initiatives aligned with the Sustainable Development Goals (SDGs), disparities continue to exist across states and socio-economic groups.

This project analyzes data from the 78th Round of the Multiple Indicator Survey (MIS) to evaluate access to improved drinking water sources across India. Using IBM Watson AutoAI, machine learning models are built and evaluated to identify patterns, disparities, and key factors influencing water accessibility.

The insights from this analysis aim to support data-driven policymaking and contribute toward achieving equitable access to clean drinking water.

## Problem Statement
The objective is to assess the percentage of the population with access to improved drinking water sources in India and analyze disparities across regions and demographic groups. The project also explores related indicators to understand broader socio-economic patterns and generate actionable insights for sustainable development.

## Dataset Information
Source: AI Kosh (IndiaAI)  
Survey: Multiple Indicator Survey (MIS), 78th Round  
Dataset Link: https://aikosh.indiaai.gov.in/web/datasets/details/improved_source_of_drinking_water_multiple_indicator_survey_78th_round.html

## Key Attributes Used  
- State  
- Sector (Urban / Rural)  
- Gender  
- Age Group  
- Access to Improved Drinking Water  
- Clean Cooking Fuel Usage  
- Migration Status  

## Tools & Technologies
- IBM Watson Studio  
- IBM Watson AutoAI  
- IBM Cloud  
- Machine Learning (Regression)  
- Data Analytics & Feature Engineering  

## Methodology  
- Data ingestion and validation in IBM Watson Studio  
- Selection of prediction target  
- Automated feature engineering using AutoAI  
- Model training and hyperparameter optimization  
- Pipeline comparison and ranking  
- Model evaluation using performance metrics  
- Interpretation of feature importance  

## Model Details  
Best Performing Model: XGBoost Regressor  
Prediction Type: Regression  
Number of Features: 6  
AutoAI Enhancements: Feature engineering and hyperparameter optimization  

## Model Evaluation Metrics  
RMSE: 3.371  
R² Score: 0.941  
Mean Absolute Error (MAE): 2.397  
Explained Variance: 0.941  

These metrics indicate strong predictive performance and reliable generalization.

## Key Insights 
- Identified regional and demographic disparities in water accessibility  
- Highlighted key factors influencing access to improved drinking water  
- Demonstrated the effectiveness of AutoAI for rapid ML experimentation  
- Supported evidence-based decision-making for public policy and sustainability.

## Conclusion  
This project demonstrates an end-to-end machine learning workflow using IBM Watson AutoAI to address a real-world public health and sustainability problem. It highlights the role of data analytics and AI in supporting social impact and SDG-focused initiatives.

## Project Screenshots

### IBM Watson AutoAI Pipeline  
![AutoAI Pipeline](https://github.com/sumakasula/drinking-water-analysis-autoai/blob/main/Screenshot%202025-07-26%20184137.png)

### Model Performance & Evaluation 
![Model Metrics](https://github.com/sumakasula/drinking-water-analysis-autoai/blob/main/Screenshot%202025-07-26%20183406.png)









