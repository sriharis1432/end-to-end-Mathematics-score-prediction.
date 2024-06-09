
# Mathematics Score Predictor




## Overview

Welcome to the Student Performance Predictor repository! This project, spearheaded with a focus on modular coding and CI/CD pipelines, is designed to analyze student information datasets. It covers intricate stages including data ingestion, transformation, model training, evaluation, and prediction pipelines. The deployment is achieved using Flask, providing a user-friendly interface for interacting with the predictor.
## Project Highlights

- **Modular Coding:** The project follows a modular coding approach for enhanced organization and maintainability.
- **CI/CD Pipelines:** Continuous Integration (CI) and Continuous Deployment (CD) pipelines are implemented using Git Actions, ensuring streamlined development practices.
- **Technologies Used:**
  - Machine Learning (Regression)
  - Python
  - Flask
  - GitHub



## Data Preprocessing

- Handle missing data and outliers.
- Convert categorical variables to numerical if necessary.
- Normalize or scale numerical features.
## Exploratory Data Analysis (EDA)
- Visualize the distribution of mathematics scores.
- Explore relationships between different features and the target variable.
## Model Selection

- Several regression models are considered, including Random Forest, Decision Tree, Gradient Boosting, Linear Regression, XGBRegressor, CatBoostRegressor, and AdaBoostRegressor.

- For each model, hyperparameters are fine-tuned using a dictionary (params) that contains potential values for specific hyperparameters.

**Best Model Selection**
- The best model is determined based on the model with the highest R-squared score. If the score is below a certain threshold (0.6), a CustomException is raised, indicating that no suitable model was found.
## Learnings
1. **Modular Coding Enhances CI/CD:**

- Code Organization: Breaking down the project into modular components improves code organization, making it easier to manage and understand during Continuous Integration/Continuous Deployment (CI/CD) processes.

- Automated Testing Advantage: Modular code facilitates focused unit testing for individual components, ensuring that changes are thoroughly tested without impacting other parts of the system.

2. **Modular Coding for End-to-End Projects:**

- Scalability and Maintenance Ease: Modular coding in end-to-end projects allows for seamless scalability. New features can be added with ease, and maintenance becomes straightforward as each module can be addressed independently.

- Collaboration Efficiency: Collaboration among team members is enhanced with modular coding. Different team members can work on distinct modules concurrently, reducing development time and increasing overall efficiency.

3. **Integration with CI/CD Streamlines Deployment:**

- Automated Builds: A modular structure supports automated builds in CI/CD pipelines. Each module can be built independently, streamlining the integration of changes into the overall system.

- Selective Deployment: Modular coding allows for selective deployment of changes, minimizing downtime. Only the modules affected by the changes need to be redeployed, contributing to a more flexible and efficient deployment process.
