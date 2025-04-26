# STAT-427_GroupProject


**Topic:** Investigating trends in MTA transit ridership recovery post-pandemic using 
statistical learning methods. 

**Summary:** For this project, we plan to apply statistical learning techniques to analyze 
NYC transit ridership recovery trends from pandemic times to now. By predicting future 
ridership trends and classifying usage patterns, the findings will offer insights into public 
transit demand shifts, which can inform future transportation policies.  

### Questions of Interest:  
  + Regression Question: Can we predict total estimated subway ridership based on pandemic/post-pandemic trends and while considering external factors such as economic indicators? 
  + Classification Question: Can we categorize daily ridership levels as “low,” “average,” or “high” based on total ridership numbers?

### Planned Methods: 
+ For Regression 
  + Multiple linear regression – to predict total daily ridership 
  + Ridge/Lasso regression – to handle multicollinearity  
  + Polynomial regression – capture potential nonlinear relationships 
+ For Classification 
  + Decision trees & Random Forest – to classify ridership days into “low,” “average,” or “high” based on percentiles of pre-pandemic ridership 
  + K-Nearest Neighbors (KNN) – for classification tasks based on proximity 
  + Quadratic Discriminant Analysis (QDA) – to model non-linear decision boundaries 
+ Cross-validation & Model Evaluation 
  + K-Fold Cross-Validation – to assess model performance 
  + Mean Squared Error (MSE) & Accuracy Metrics – for model comparison 


### Group Member Responsibilities: 
+ Data Cleaning & Preparation: J-La 
+ Regression Modeling & Analysis:  
  + J-La: 
    + Regression: Multiple Linear Regression 
    + Classification: K-Nearest Neighbors (KNN) 
    + Cross-Validation & Model Evaluation: K-Fold CV for MLR & KNN + MSE for MLR 
  + Kennedy: 
    + Regression: Ridge/Lasso Regression  
    + Classification: Decision Trees & Random Forest 
    +  Cross-Validation & Model Evaluation: K-Fold CV for Ridge/Lasso & Decision Trees + Model Accuracy Metrics for Decision Trees 
  + Leigh: 
    + Regression: Polynomial Regression 
    + Classification: Quadratic Discriminant Analysis (QDA) 
    + Cross-Validation & Model Evaluation: K-Fold CV for Polynomial Regression & QDA + MSE for Polynomial Regression & Accuracy Metrics for QDA 
+ Visualization & Presentation Design: All members 
+ Report Writing & Editing: All members
