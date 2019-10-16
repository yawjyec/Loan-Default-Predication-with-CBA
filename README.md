# Optimizing Profit by Predicting Loan Default and Using Cost-Benefit Anlaysis
This is Metis Project 5.

## Objective
The objective of this project is to predict the probability of loan default of lending business and use Cost-Benefit Analysis to optimize the profit. The data used for this project is from Home Credit (an international non-bank financial institution founded in 1997 in the Czech Republic and headquartered in Netherlands) obtained from Kaggle competition. Due to the imbalanced classes in the dataset, oversampling was used to improve the performance of model prediction.

## Data Source
Link for data: https://www.kaggle.com/c/home-credit-default-risk/data

There are 8 tables and over 58 million rows of data. All tables were evaluated but only codes using tables application_train.csv, bureau.csv, bureau_balance.csv and previous_application.csv
are listed in this depository. 

## Source Codes
There are five Jupyter notebooks used for this project. Description of each notebook are listed below:

1.	main.ipynb
*	This is the main notebook, which contains source code of data preprocessing, exploratory data analysis, feature engineering, model evaluation & selection and cost-benefit analysis using application_train.csv.
2.	EDA.ipynb
*	This notebook contains additional exploratory data analysis using application_train.csv. The result of analysis from this notebook was used to for feature selection and feature engineering in the main notebook.
3.	cost_benefit_analysis.ipynb
*	This notebook shows how cost and benefit were derived.
4.	bureau.ipynb
*	This notebook shows how additional features from bureau.csv and bureau_balance.csv were preprocessed, analyzed, engineered and selected. Features from this notebook were later combined with main notebook for final modeling.
5.	previous_application.ipynb
*	This notebook shows how additional features from previous_application.csv were preprocessed, analyzed, engineered and selected. Features from this notebook were later combined with main notebook for final modeling.

## Final Product
Please see <Loan_Default_CBA_Presentation.pdf> for final product of this project.
