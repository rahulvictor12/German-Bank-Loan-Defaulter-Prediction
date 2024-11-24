# German-Bank-Loan-Defaulter-Prediction
# **Predicting Loan Default: A Machine Learning Approach to Assessing Risk in a German Bank's Customer Base**

In this study, we dig deeper into the factors that contribute to loan defaults among applicants in the German lending market. We analyse the German Credit Risk dataset, which contains numerous facts about loan applicants and their credit histories, to determine the impact of these parameters to the likelihood of loan default and credit risk rating. The goal of this investigation is to create predictive models that can help identify potential defaults.
##  Contents

-   Import: Importing the required libraries and an overview of the dataset
-   Loading the dataset: Reads input data from a CSV file called German_Bank.csv.
-   Data Overview and Statistical Summary: Understand the data, find missing values and duplicated values,     and provide a provide a statistical summary for numeric variables.
-   EDA: exploratory data analysis to understand the relationship among different predictors and their         correlation with the target variable.
-   Data Processing: Handles missing values and encodes categorical variables.
-   Model Training: Trains various machine learning models, including Bagging, Random Forest, GBM,             AdaBoost, and XGBoost.
-   Hyperparameter Tuning: Uses Grid Search and Random Search for Hyperparameter Optimisation.
-   Model Evaluation: Evaluates models using metrics such as accuracy, recall, precision, and F1 score.
-   Conclusion: Recommends the best-fit model for the given problem statement.

## About Dataset:
The data set has 17 columns and 1000 rows. Columns are described below and each row is a customer. 

- checking_balance - Amount of money available in account of customers
- months_loan_duration - Duration since loan taken
- credit_history - credit history of each customers
- purpose - Purpose why loan has been taken
- amount - Amount of loan taken
- savings_balance - Balance in account
- employment_duration - Duration of employment
- percent_of_income - Percentage of monthly income
- years_at_residence - Duration of current residence
- age - Age of customer
- other_credit - Any other credits taken
- housing- Type of housing, rent or own
- existing_loans_count - Existing count of loans
- job - Job type
- dependents - Any dependents on customer
- phone - Having phone or not
- default - Default status (Target column)

## Dependencies

- Python3
- Pandas
- Numpy
- Statistics
- scikit-learn
- matplotlib
- seaborn
- xgboost
- sklearn





## Project Structure
```
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── GermanBankLoanDefaultPredictionReport.pdf        <- Report produced for the analysis
│   └── figures        <- Generated graphics and figures to be used in reporting
│       ├── CategoricalFeaturesRelationToTarget.png      <- Categorical features relation to target
│       └── NumericFeaturesRelationToTarget.png          <- Numeric features relation to target
│
├── src                <- Source code for use in this project.
│   ├── GermanBankLoanDefaultPredictor.ipynb     <- Scripts that contain Scripts for data manipulation,build and evaluate models.
│   ├── GermanBankLoanDefaultPredictor.html     <- HTML file containing the outputs and results from the Scripts of data manipulation, and evaluated models.

```
## Getting Started 

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

- Install dependencies included in README.md

- Run the GermanBankLoanDefaultPredictor.ipynb file




## Authors

#### Rahul Victor Sunkara 
- Email - rahulvsunkara@arizona.edu
- Git - [@rahulvictor12](https://www.github.com/rahulvictor12)

