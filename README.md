# SpaceX Machine Learning Prediction

The goal of this project is to build a machine learning model that predicts whether a SpaceX rocket launch will land successfully or not. The project consists of five parts:

1. **Data Collection**: This part focuses on collecting data from various sources, including the SpaceX API and Kaggle.
2. **Data Preprocessing**: This part focuses on cleaning and preprocessing the data, including handling missing values, encoding categorical variables, and scaling numerical variables.
3. **Feature Engineering**: This part focuses on creating new features from the existing data, including creating dummy variables, polynomial features, and interaction features.
4. **Model Training**: This part focuses on training a machine learning model on the preprocessed data, including splitting the data into training and testing sets, selecting a model, and evaluating the model's performance.
5. **Model Deployment**: This part focuses on deploying the machine learning model, including saving the model to a file, loading the model from a file, and making predictions on new, unseen data.

## Requirements

To run this project, you will need the following:

* Python 3.x
* Pandas
* NumPy
* Scikit-learn
* Joblib
* Jupyter Notebook


## Usage

To use this project, follow these steps:

1. Install the required packages using `pip install -r requirements.txt`.
2. Open the Jupyter Notebooks in order and follow the instructions in each notebook.
3. Save the trained model to a file using `joblib.dump(model, 'model.joblib')`.
4. Load the trained model from a file using `model = joblib.load('model.joblib')`.
5. Make predictions on new, unseen data using `predictions = model.predict(new_data)`.

