# Predictive Modeling for Voter Turnout in the US Presidential Elections 2024
![Alt Text](ELECTION.webp)
##### Image Source:naem021/Big Stock Photo

# Summary
This project aimed to predict voter turnout in the upcoming US presidential election using data from the CCES survey. Employing machine learning algorithms like XGBoost and Ranger, the study tackled challenges such as imbalanced data and complex dataset characteristics. Key steps included preprocessing the dataset with methods like Multiple Imputation by Chained Equations (MICE) for handling missing data and selecting pertinent features using SHAP analysis.

The evaluation of algorithms focused on practical metrics like recall, F1 score, and Precision-Recall Area Under the Curve (PR-AUC), emphasizing the models' ability to accurately predict non-voters. XGBoost, after rigorous tuning, emerged with a recall of 0.82 and PR-AUC of 0.83, showcasing its effectiveness in identifying individuals less likely to vote.

These findings highlight the significance of precise voter turnout predictions for targeted civic engagement strategies. By integrating demographic weights and optimizing feature selection, the model provided robust insights into voter behavior, essential for enhancing democratic participation and representation.This study demonstrates the practical application of machine learning in electoral forecasting, paving the way for more informed decision-making in electoral campaigns and policy initiatives aimed at increasing voter engagement. Future research could expand on these methods to improve predictive accuracy across diverse electoral contexts and demographic groups.

# Technical Skills and Tools
| Aspect                   | Details                                                                                                                                                          |
|--------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Data Preprocessing**       | Employed Multiple Imputation by Chained Equations (MICE) for handling missing data <br> One-hot encoding of categorical variables for improved model interpretability |
| **Machine Learning Algorithms** | XGBoost: Utilized gradient boosting for robust handling of high-dimensional data and class imbalance<br>Ranger (Random Forests): Implemented ensemble learning for stable and accurate predictions |
| **Feature Selection**       | Applied SHAP (SHapley Additive exPlanations) to interpret feature importance, enhancing transparency by visualizing each feature's impact on predictions            |
| **Model Evaluation**         | Evaluated using metrics: Recall, F1 score, Precision-Recall AUC <br> Hyperparameter Tuning: Grid search for optimizing model parameters                          |
| **Programming Language**     | R: Utilized for data manipulation, preprocessing, and modeling with tidyverse, caret, xgboost, and SHAPforxgboost packages                                          |

# Data Source
Schaffner, B., Ansolabehere, S., & Shih, M. (2023). Cooperative Election Study Common Content, 2022 (Version V4). Harvard Dataverse. https://doi.org/10.7910/DVN/PR4L8P
