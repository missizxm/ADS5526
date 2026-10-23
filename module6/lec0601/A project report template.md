## Project Title
### Abstract 
Briefly summarize:
- Problem
- Dataset
- Methods
- Key findings

### 1. Introduction
#### Background
Provide the context and motivation for the problem being addressed. Explain why the outcome of interest is important, who may benefit from accurate predictions, and summarize relevant domain knowledge or prior work that motivates the analysis.
#### Research Question
Clearly state the primary research question that the project seeks to answer. 
**Example:**
> Can patient demographic, behavioral, and clinical characteristics be used to accurately predict the likelihood of developing diabetes?
#### Predictive Objective
Define the prediction task and outcome variable.
- The target variable (outcome) being predicted.
- Whether the task is classification, regression, or another type of predictive task.
- The prediction horizon, if applicable (e.g., 30-day readmission, annual risk, future sales).
**Example:**
> The objective is to develop and compare predictive models that classify individuals as having high or low risk of food insecurity based on demographic and socioeconomic characteristics.
#### Setting and Use Case
Describe the real-world setting in which the model could be applied, addressing the following questions:
- Who are the end users of the model?
- When and where would predictions be generated?
- What decisions could be influenced by the model outputs?
- What operational or practical constraints exist?
**Example:**
> The model is intended for use by community organizations and policymakers to identify households at elevated risk of food insecurity. Predictions could be used to prioritize outreach efforts, allocate limited resources, and inform intervention planning.
#### Potential Impact
Discuss the value and implications of the predictive model, considering:
- Potential benefits of accurate predictions.
- How the model could improve decision-making.
- Economic, clinical, public health, educational, or organizational impact.
- Ethical considerations, fairness concerns, and limitations that may affect deployment.
**Example:**
> If successfully implemented, the model could help direct assistance toward high-risk households before severe food insecurity occurs. Early identification may improve resource allocation efficiency and support more targeted interventions. However, model performance should be evaluated across demographic groups to ensure equitable and responsible use.

### 2. Dataset Description
#### Data Source
Describe where the data originated and how it was obtained.
#### Variables
Summarize the important variables used in the analysis. We often prepare a data dictionary or codebook to provide metadata about a dataset.
#### Challenges 
Discuss relevant data issues, including:
- Missingness
- Skewness
- Class imbalance
- Collinearity
- High dimensionality

### 3. Exploratory Data Analysis
#### Descriptive Statistics
#### Data Quality Assessment
- Missing values
- Skewed distributions
- Outliers
- Other data quality issue
#### Distribution Assessment
Describe the distribution of key variables.
#### Correlation Analysis
Assess relationships among variables.
#### Visualization Results
Include figures and discussion.

### 4. Data Preparation
#### Train/Test Split Strategy
#### Data Issue Handling
#### Transformation of Variables
#### Feature Engineering
Explain newly created variables or derived features.
#### Collinearity Assessment
Describe methods used to evaluate and handle collinearity.
#### Final Input Dataset
Provide a summary of the final dataset used for modeling.

### 5. Modeling Methods
Provide the following information for each modeling method:
##### Method Description
##### Model Specification
Provide model formula and assumptions.
##### Hyperparameter Selection
List candidate hyperparameters and rationale.
##### Tuning Procedure
Describe parameter selection and optimization.

All work must be reproducible, which requires:
- Random seeds
- Documented preprocessing
- Well-commented code
- Clear workflow organization
### 6. Model Evaluation
#### Evaluation Metrics
Select evaluation metrics and justify the selected metrics and additional considerations. Discuss:
- What aspect of model performance the metric measures.
- Why the metric is appropriate for the problem.
- Situations where the metric may be misleading.
- Strengths and limitations of the metric in the context of the dataset and prediction objective.

Model evaluation should extend beyond a single performance metric. Consider and discuss:
- Cross-validation results and variability across folds
- Generalization to unseen data
- Overfitting and underfitting
- Class imbalance
- Calibration of predicted probabilities
- Robustness to outliers and influential observations
- Model complexity and computational efficiency
- Reproducibility and stability of results
- Practical considerations such as interpretability and deployment feasibility
#### Cross-Validation Strategy
Describe resampling and validation procedures.
#### Comparative Performance
Provide tables and visualizations related to model comparison. 

### 7. Model Selection & Interpretation
#### Selected Model
Identify the final model and justify the selection.
#### Coefficient Interpretation
Interpret important coefficients (if applicable).
#### Model Diagnostics
Present diagnostic results and assumptions checks.
#### Feature Importance
Discuss the most influential predictors.
#### Explainability 
Describe model interpretability approaches and discuss the results, addressing the following questions:
- Which variables appear to be the most influential predictors?
- How do key predictors affect the outcome?
- Are the effects consistent with domain knowledge and prior expectations?
- Are there unexpected relationships or findings?
- What limitations exist when interpreting the selected model?
- What insights can be gained for decision-making, future research, or practical implementation?

see: Fridkin, S., and M. Bendersky. 2026. “ _Interpretable Machine Learning: A Comprehensive Review of Foundations, Methods, and the Path Forward_.” _Wiley Interdisciplinary Reviews: Data Mining and Knowledge Discovery_ 16, no. 1: e70075. [https://doi.org/10.1002/widm.70075](https://doi.org/10.1002/widm.70075).

### 8. Discussion
#### Major Findings
#### Strengths and Limitations
#### Practical Implications
#### Future Improvements

### References
### Appendix
#### A. Additional Tables
#### B. Additional Figures
#### C. Hyperparameter Grids
Document all hyperparameter search spaces and tuning results.
#### D. Supplementary Diagnostics
Provide additional model diagnostics, validation results, and sensitivity analyses.
### AI Use Disclosure
Describe any AI tools used during the project, covering:
- AI tool(s) used
- How they were used
- Extent of use
- Verification process performed 
**Example**: https://panbibliotekar.github.io/gaidet-declaration/ 
