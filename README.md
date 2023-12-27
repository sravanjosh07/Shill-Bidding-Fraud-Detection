# Shill Bidding Fraud Detection - Project Overview

## Introduction
This repository contains the work and findings of our project, "Shill Bidding Fraud Detection," conducted as part of the EDS 6340 - Introduction to Data Science course at the University of Houston, Spring 2023. The project aims to detect fraudulent bidding activities in online auctions using advanced machine learning techniques. We utilized the Shill Bidding Dataset from the UCI machine learning repository, focusing on binary classification to discern between normal and fraudulent bids.

## Project Structure
The repository is organized as follows:

- `/notebook/`: Contains Jupyter notebooks for each model run and their results.
- `/data/`: Dataset used in the project.
- `/figures/`: Visualizations and plots generated during the analysis.
- `README.md`: Provides an overview and instructions for the project.

## Key Components
### Data Pre-processing
- **Objective**: Cleaning and preparing raw data for analysis.
- **Approach**: Handling missing values, outliers, and transforming data into a usable format.

### Model Development and Testing
- **Techniques Used**: Logistic Regression, K-Nearest Neighbors Classifier (KNN), Support Vector Machines (SVM), Random Forest Classification, and Extreme Learning Machines (ELM).
- **Evaluation**: Performance metrics like accuracy, precision, recall, and F1-score were used to assess each model.

### Feature Selection
- **Methods**: Employed Lasso and bi-directional elimination for selecting relevant features.
- **Impact**: Enhanced model performance and interpretability by reducing feature space.

### Clustering and Visualization
- **Purpose**: Explore data patterns and understand dataset structure.
- **Tools**: Employed clustering techniques and visualization tools like PCA.

### Ensemble Modeling
- **Strategy**: Combined different models using techniques like stacking to improve predictive accuracy.
- **Result**: Achieved robust and reliable predictions for shill bidding detection.

## Findings and Conclusion
The project successfully demonstrated the application of machine learning techniques in detecting shill bidding activities in online auctions. Key insights include:
- The significance of thorough data preprocessing and feature selection in building effective models.
- The effectiveness of ensemble modeling in enhancing prediction accuracy.
- The importance of visualizations in understanding data patterns and model performance.

Our findings contribute to the field of online fraud detection, showcasing the potential of machine learning in addressing complex real-world problems.

## Usage
To replicate or build upon our findings, follow these steps:
1. Clone the repository.
2. Navigate to the `/notebook/` directory to access model notebooks.
3. Run Jupyter notebooks to see the model building process and results.
4. Explore `/data/` and `/figures/` for dataset and visualizations, respectively.

## Collaboration
This project was a collaborative effort, showcasing the importance of teamwork and diverse skill sets in solving data science challenges.

## License
This project is open-source and available for educational and research purposes.

---

We hope our project will serve as a valuable resource for those interested in machine learning and fraud detection in online auctions.
