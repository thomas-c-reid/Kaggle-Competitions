1) Titanic Competition
  For this competition I performed data preprocessing techniques and a sequential keras model to predict which passengers would be expected to survive the crash of the titanic
  SCORE: 0.74641

# Kaggle Competition Solutions

Welcome to my GitHub repository showcasing my solutions to various Kaggle competitions! Below, you'll find a collection of Jupyter notebooks detailing my approaches, methodologies, and code implementations for tackling different data science challenges hosted on Kaggle.

## Competitions Included:

### Titanic - Machine learning from disaster:

- **Description**: Use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.
- **My Approach**: Using several data pre-processing techniques and a simple keras sequentail network i was able to build a model that could predict the outcome of passengers onboard the titanc
- **Results**: The basic model had an accuracy of 0.74641.
- **Takeaways**: This was my first kaggle competition entered and soon realised that I would need to expand the machine learning algorithms and data pre-processing techniques that are required to create accurate models

### Steel Plate Defect Prediction:

- **Description**: Predict the probability of various defects on steel plates.
## My Approach:

For each competition, I adopted a systematic approach to tackle the given problem. Initially, I experimented with different preprocessing techniques to optimize the performance of the models. Despite building a pipeline with minimal preprocessing, I found that it didn't significantly improve the area under the curve (AUC) score.

In the preprocessing phase, I experimented with several techniques, including log transformations to address skewed data distributions, scaling features to ensure uniformity across different scales, and dropping unimportant columns to reduce noise in the dataset.

Following preprocessing, I employed the XGBoost algorithm, leveraging its powerful capabilities in handling complex data and producing accurate predictions. To fine-tune the model and optimize its performance, I conducted hyperparameter tuning, exploring various combinations of hyperparameters to arrive at an optimal configuration.

By combining these preprocessing techniques and utilizing advanced algorithms like XGBoost along with careful hyperparameter tuning, I was able to develop highly accurate models that yielded competitive results in the Kaggle competitions I participated in.
- **Results**: Current AUC score of 0.89345, 272/1072
- **Takeaways**: This was my first kaggle competition entered and soon realised that I would need to expand the machine learning algorithms and data pre-processing techniques that are required to create accurate models

