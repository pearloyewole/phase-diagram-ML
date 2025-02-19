# phase-diagram-ML
Code for phase diagram prediction from my research project last summer. I learned a lot from my previous machine learning research project https://github.com/pearloyewole/Predict-Student-Grades, and have applied the learned practices in this project (such as a larger dataset, cross validation, and working with more complex machine learning algorithms)


# Methodology: 
- Collect data from literature ~2000 experimental PT points
- Label data based on ice phases and other identifying information
- Split data into test set (30 percent) and train set (70 percent)
- With the train set I identified hyperparameters and conducted a grid search with cross validation
- Once I found an optimized model we calculated a final score and from the test score and the train score.
- I used the parameters from the model with the highest score to predict ice phase melting curve 
