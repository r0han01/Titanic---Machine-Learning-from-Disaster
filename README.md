# Titanic-Machine-Learning-from-Disaster
Predict survival on the Titanic

Project Overview:
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, resulting in the deaths of a large number of passengers and crew. This project aims to analyze passenger data and predict whether a passenger survived the disaster or not.

Data:
📊📉📈
The project utilizes a dataset containing information about passengers aboard the Titanic, including features like age, gender, ticket class, fare, cabin, and more. The dataset is divided into a training set and a test set. The training set is used to train machine learning models, while the test set is used to evaluate the model's performance.

Data Preprocessing:

Combining Data: 🔄 The training and test datasets are combined for preprocessing and feature engineering.
Handling Missing Values: 🛠️ Any rows with missing values are removed from the dataset.
Feature Engineering:
Encoding Categorical Variables: 🔤 Categorical variables like "Sex" and "Embarked" are encoded using label encoding.
Extracting Titles: 👑 Titles are extracted from passenger names, and certain rare titles are grouped together.
Creating New Features: 🔍 A new feature "FamilySize" is created by combining the number of siblings/spouses and parents/children aboard.
Model Selection and Hyperparameter Tuning:
🔍 Gradient Boosting Classifier is chosen as the machine learning model for this project. Hyperparameters such as the number of estimators, learning rate, and max depth are tuned to find the combination that yields the best performance.

Model Evaluation:
📊 The models are trained using different hyperparameter combinations, and their accuracies are evaluated using a validation set. The model with the highest accuracy is selected as the final model for making predictions.

Conclusion:
🏆 The project concludes with identifying the model with the highest accuracy and its corresponding hyperparameters. This model can then be used to predict survival outcomes for passengers in the test dataset.

By following this approach, the project aims to demonstrate the application of machine learning techniques in predicting survival on the Titanic based on passenger information.

![footer-bg](https://github.com/r0han01/Titanic---Machine-Learning-from-Disaster/assets/168735672/f6660c84-309c-40ea-aa38-483d3839bf31)

