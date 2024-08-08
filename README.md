# PRODIGY_ML_01

Project Description:

This project aims to predict the sale prices of residential homes using a linear regression model. The dataset used for this project includes various features related to the properties, such as the above-ground living area (square footage), the number of bedrooms, and the number of bathrooms. The target variable is the sale price of the properties.

The goal is to build a model that can accurately predict house prices based on these features, providing insights into how different factors contribute to the overall property value. The project involves data preprocessing, feature engineering, model training, and evaluation, as well as generating predictions for unseen data.
Key Features:

    GrLivArea (Above Ground Living Area in Square Feet): Represents the total above-ground (excluding basement) living area of the house.
    BedroomAbvGr (Number of Bedrooms Above Ground): Indicates the number of bedrooms in the house.
    FullBath & HalfBath: Represent the number of full and half bathrooms, respectively. These features are combined into a new feature called TotalBath to simplify the model.

Model Explanation:

The model is built using linear regression, a fundamental machine learning algorithm that assumes a linear relationship between the input features and the target variable. The selected features are used to train the model, which is then evaluated on a validation set using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

The linear regression model is chosen for its simplicity and interpretability, making it a suitable choice for understanding how each feature impacts the sale price.
Project Workflow:

    Data Loading and Exploration: Load the dataset and perform an initial exploration to understand the structure and distribution of the data.
    Data Preprocessing: Handle missing values, create new features (e.g., TotalBath), and prepare the data for modeling.
    Model Training: Train a linear regression model using the selected features.
    Model Evaluation: Evaluate the model's performance using appropriate metrics and visualize the results.
    Prediction: Use the trained model to predict sale prices on a test dataset and prepare a submission file.
    User Interaction: Implement a function allowing users to input their own property details and receive a predicted sale price.

Results:

The model's performance is measured using RMSE and MAE, providing an indication of how well the model can predict sale prices. Visualizations are included to compare actual vs. predicted prices and to analyze the distribution of predicted prices.

This project demonstrates the practical application of linear regression in real estate, offering valuable insights into how different property features influence house prices.
