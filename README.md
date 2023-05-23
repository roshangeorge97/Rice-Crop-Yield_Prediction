# Predicting Rice Yields in Vietnam using Satellite Data

This project aimed to develop a regression model for predicting rice yield in Vietnam using satellite data. The project was motivated by the fact that rice is a staple food for more than four billion people and a livelihood for a fifth of the world's population. However, the amount of land available for rice and the yield growth rates are in decline, with irrigated rice yields in developing countries forecast to decrease by 15% due to climate change. Therefore, solutions focused on this staple are scalable and could transform global rice production.

## Project Overview

The project used rice yield data from Chau Thanh, Thoai Son, and Chau Phu regions of Vietnam as the target variable. The predictor variables were satellite data available on Microsoft Planetary Computer portal. An example Jupyter notebook was built, which had a preliminary R2 score. The notebook connected to public-facing data sources on Microsoft's Planetary Computer. The output of the notebook was a .csv file that could be uploaded to the challenge platform, which could be improved over the course of the challenge.

Opportunities for improvement included but were not limited to exploring data from multiple satellites, using combinations of bands from satellite, generating various vegetation indices to be used as features, building bounding boxes of different sizes around the given latitude and longitude positions, trying other regression algorithms, and hyperparameter tuning.

## Data CollectionThe markdown code for the remaining part of the Github README file:

The rice yield data from Chau Thanh, Thoai Son, and Chau Phu regions of Vietnam were obtained from a public dataset. The satellite data were obtained from the Microsoft Planetary Computer portal. The satellite data included spectral bands, which were used to generate vegetation indices.

## Data Preprocessing
The rice yield data were preprocessed to remove any missing values and outliers. The satellite data were preprocessed to remove any noisy data and to normalize the data.

## Feature Engineering
Various vegetation indices were generated using the satellite data as features. These included NDVI, EVI, and SAVI. Bounding boxes of different sizes were created around the given latitude and longitude positions.

## Model Selection
Several regression algorithms were tried, including Linear Regression, Random Forest Regression, and Gradient Boosting Regression. The best performing algorithm was selected based on the R2 score.

## Hyperparameter Tuning
The hyperparameters of the best performing algorithm were tuned using Grid Search and Random Search. The best hyperparameters were selected based on the R2 score.

## Model Evaluation
The final model was evaluated using the test dataset. The evaluation metrics included R2 score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

## Conclusion
In conclusion, a regression model was developed for predicting rice yield in Vietnam using satellite data. The model achieved a high R2 score and performed well onthe test dataset. The model could be used to predict rice yield in other regions of Vietnam and could be extended to other crops and regions.

