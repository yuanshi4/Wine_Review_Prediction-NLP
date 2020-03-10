# Wine_Review_Prediction_and_Natural_Language_Processing
- Wine Reviews  - 130k wine reviews with variety, location, winery, price, and description, my goal is to process text and use available info mentioned to predict wines' ratings. 

- For this project, we are interested in creating predictive models that predicts points (ratings) rated by WineEnthusiast on a scale of 1 to 100. Such points can be meaningful to determine how good a out-of-book wine is. 

- The Wine Review dataset contains 129971 observations and 14 variables, among the 14 variables, there are only 1 variable is numeric while everything else are categorical. 

- Also, missing data is involved and there are a lot of levels in those categorical variables. 

- I decided to build a Catboost model, which a gradient boosting model with categorical support out of the box, and a random forest model, which is also a tree-based model, but it takes a different approach. 

- In summary, the Catboost model performs better than Random Forest model with a RMSE of 1.71 on Test set compared to a RMSE of 1.85 from a random forest model. Parameter-tuning and additional processing taken for each method will be further discussed in this report in the next few sections.
