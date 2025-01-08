# Impact of Air Pollution on Chronic Lung Disease

## Overview
This repository contains the final report for a project analyzing the **impact of air pollution on the prevalence and severity of chronic lung disease**, conducted as part of STA303 coursework. The study employs a multinomial logistic regression approach to investigate the relationships between air pollution levels, demographic factors, and health-related variables.

## Project Motivation
Air pollution is a significant health concern, particularly in urban areas with high pollution levels, such as Ulaanbaatar, Mongolia. This study aims to explore how varying levels of air pollution affect chronic lung disease severity, with the goal of informing public health policy and preventative measures.

## Key Features of the Study
- **Advanced Statistical Analysis**: A multinomial logistic regression model was used to capture the gradations in lung disease severity and air pollution exposure.
- **Data Sources**: The dataset includes 1000 cases with complete data, featuring variables such as air pollution levels, age, smoking habits, and genetic risk factors.
- **Validation and Diagnostics**:
  - 10-fold cross-validation to ensure model consistency.
  - ROC curve analysis and calibration plots to assess predictive accuracy and reliability.

## Repository Structure
The repository is organized as follows:
- `report/`: Contains the final report in PDF format.
- `data/`: Includes a description of the dataset and a link to its source on Kaggle.
- `scripts/`: Contains the R scripts used for data preprocessing, model fitting, and visualization.
- `results/`: Includes visualizations, residual plots, and validation metrics.

## Key Findings
- Higher levels of air pollution are strongly associated with increased severity of chronic lung disease.
- Genetic risk factors amplify the impact of pollution on lung health.
- The multinomial logistic regression model demonstrated excellent predictive accuracy, with an AUC greater than 90%.

## Challenges and Limitations
- **Cross-Sectional Design**: Limits the ability to establish causality.
- **Data Imbalances**: Disproportionate sample sizes across categories required careful consideration during modeling.
- **Technical Constraints**: Issues with generating calibration plots for the highest severity level of lung disease.

## Future Work
The study highlights the need for longitudinal research to better understand the dynamic relationship between air pollution and lung health. Further exploration of genetic-environment interactions is also recommended.

