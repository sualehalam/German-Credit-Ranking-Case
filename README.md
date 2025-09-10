# Credit Risk Analysis


### Credit risk
Credit Risk is the probable risk of loss resulting from a borrower's failure to repay a loan or meet contractual obligations. If a company offers credit to its client,then there is a risk that its clients may not pay their invoices.

### Types of Credit Risk
**Good Risk**: An investment that one believes is likely to be profitable. The term most often refers to a loan made to a creditworthy person or company. Good risks are considered exceptionally likely to be repaid.

**Bad Risk**: A loan that is unlikely to be repaid because of bad credit history, insufficient income, or some other reason. A bad risk increases the risk to the lender and the likelihood of default on the part of the borrower.

### About Dataset

The original dataset contains 1000 entries with 20 categorial/symbolic attributes prepared by **Prof. Hofmann**. In this dataset, each entry represents a person who takes a credit by a bank. Each person is classified as good or bad credit risks according to the set of attributes. The link to the original dataset can be found below.

### Dataset Description

- **Source**: UCI Machine Learning Repository  
- **Link**: [German Credit Dataset](https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data)  
- **Size**: 1000 entries  
- **Features**: 20 independent variables (13 categorical, 7 numerical)
- - **Target Variable**: `Cost Matrix (Risk)` — Good Risk (1) or Bad Risk (2)  


### Columns Description


| Feature                          | Type       | Description                                                                 |
|----------------------------------|------------|-----------------------------------------------------------------------------|
| Status of existing checking acct| Categorical| e.g., "<0 DM", ">= 200 DM", "no account"                                   |
| Duration in month               | Numerical  | Duration of credit in months                                               |
| Credit history                  | Categorical| Record of borrower’s previous credit behavior                              |
| Purpose                         | Categorical| Reason for applying the loan (e.g., car, furniture, education)             |
| Credit amount                   | Numerical  | Amount of credit requested                                                 |
| Age in years                    | Numerical  | Age of borrower                                                            |
| ...                             | ...        | (Full variable description is included in the code)                        |




## Objective

To build a model that classifies individuals as **Good Risk** or **Bad Risk** using historical loan and borrower attributes.


### Future Work

1. Hyperparameter tuning using GridSearchCV

2. SHAP values for model interpretability

3. Dimensionality Reduction using PCA (Principal Component Analysis)

4. Techniques like SMOTE (Synthetic Minority Over-sampling Technique) for Addressing Class Imbalance 

