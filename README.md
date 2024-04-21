# COGNORISE-INFOTECH-DATA-SCIENCE-HACKATHON
##
# Overview
This repository contains my submission for the CognoRise InfoTech Data Science Hackathon - April 2024 edition. The goal of this hackathon is to solve a classification problem using machine learning techniques and provide a detailed analysis of the data.
This structure includes:

- `README.md`: This file contains information about the project.
- `src/`: This directory contains the source code files:
  - `N1ExploratoryDataAnalysis.ipynb`: Jupyter Notebook for Exploratory Data Analysis.
  - `N2credit_predict.ipynb`: Jupyter Notebook for credit prediction on the training data.
  - `N3credict_predict_test_data.ipynb`: Jupyter Notebook for credit prediction on the test data.
- `requirements.txt`: This file lists the project's dependencies.
- `submissions/`: This directory contains the submission files:
  - `predictions_train.csv`: Predictions on the training data.
  - `test_predictions.csv`: Predictions on the test data.


## Approach
### 1. Exploratory Data Analysis (EDA)
- Performed univariate analysis using techniques like histograms, density plots, and box and whisker plots to understand each attribute independently.
- Analyzed categorical variables using appropriate visualizations.
- Conducted multivariate analysis using scatter plots and correlation matrices to explore relationships between variables.

![image](https://github.com/vyshnaviK18/COGNORISE-INFOTECH-DATA-SCIENCE-HACKATHON/assets/113926615/6a7b2c9c-7ae1-4863-9d12-bfd20b2ece79)

![image](https://github.com/vyshnaviK18/COGNORISE-INFOTECH-DATA-SCIENCE-HACKATHON/assets/113926615/92843e9f-0742-4725-b724-803c05fa3400)

### 2. Data Preprocessing and Cleaning
- Handled missing values in categorical data using mode imputation.
- Performed other necessary data cleaning and preprocessing steps.

![image](https://github.com/vyshnaviK18/COGNORISE-INFOTECH-DATA-SCIENCE-HACKATHON/assets/113926615/7bac565b-cc49-4524-b795-9f864bec73f6)


### 3. Model Building and Training
#### Machine Learning Models
The following machine learning models were trained and evaluated on the training data:

- **Linear Regression**
- **Decision Trees**
- **Random Forests**
- **Support Vector Machines (SVMs)**
  - To improve the performance of SVMs, we used `GridSearchCV` to tune the `C` and `gamma` parameters.
- **XGBoost Classifier**

#### Model Evaluation and Selection
- Split the data into training and validation sets.
- Trained and evaluated each model using appropriate evaluation metrics (e.g., accuracy, precision, recall, F1-score).
- Selected the best-performing model(s) based on the evaluation results.

### 4. Testing and Submission
- Applied the selected model(s) to the test data.
- Generated predictions on the test data.
- Saved the test predictions in `submissions/test_predictions.csv`.

## Requirements
The required dependencies for this project are listed in the `requirements.txt` file.

## Usage
To reproduce the analysis and results, follow these steps:
1. Clone the repository: `git clone https://github.com/your-repo.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Open the Jupyter Notebooks in the `src/` directory and run the cells.

## Acknowledgments
- CognoRise InfoTech for organizing this hackathon.
- Relevant data sources and libraries used in this project.

## Contact
For any questions or inquiries, please contact [vyshnavikannan27@gmail.com].
