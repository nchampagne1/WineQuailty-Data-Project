# 🍷 Aged to Perfection: Red Wine Analytics

The most popular type of wine globally, red wine’s popularity stretches as far back as the sandy deltas of Ancient Egypt. Data gathered from Kaggle in creating this report, aims to give a detailed overview on red variants of the Portuguese "Vinho Verde" wine.

## 🍷 Data Visualization: Heat Map

Heat Maps visualizes the correlation matrix of selected columns in our dataset. The heatmap ranges from 1 to -1, indicating high correlation and low correlation respectively. For instance, desinty and fixed acidity are highly correlated indicated by their maxtrix value. Based on the negative values generated for pH and fixed acidity, we learn that theyre values have no correlation at all.
![image](https://github.com/user-attachments/assets/13d735e7-b618-4d54-b0f1-4c46d8759b0f)

## 🍷 Data Visualization: Line Graph

This line graph shows the relationship between the Wine Density and pH. The density peaks when the pH level is 3 which indicates acidity. The further proves that high correlation they demostrated from the Heat Map.
![image](https://github.com/user-attachments/assets/c0c9a0e6-e93e-4203-885a-c57dbf8bc6fb)

## 🍷 Data Visualization: Bar Graph - Feature Importance

In Tree-Based Models (like Random Forest), feature importance is calculated based on the reduction in impurity (e.g., Gini impurity or entropy) when the feature is used to split data in decision trees. Features that result in larger reductions in impurity are considered more important. 
- High importance: Features that significantly influence the target variable.
- Low importance: Features that have little to no influence on predictions.
![image](https://github.com/user-attachments/assets/8e510be1-eccc-413d-a90a-25686d191239)

## 🍷 Data Visualization: Decision Tree

The accuracy score computed by the Decision Tree model is 0.58. 

Although the score indicates it didn't predict very well. The score of 58% shows the model can predict wine quality better than random guessing. Some explanations for this score could be that the features don't fully capture all the factors that affect wine quality.
![image](https://github.com/user-attachments/assets/c7b48b98-bb50-4745-9759-7ac8c0e8c111)

## 🍷 Data Visualization: Random Forest

The accuracy score computed by the Random Forest model is 0.70. Reflecting good overall performace.
![image](https://github.com/user-attachments/assets/3f3127c5-55d9-4662-a5de-dac6f3400d30)

## 🍷 Conclsuion

We determined that RandomForest did a better job on our features because…..

- Class Imbalance Handling: Random Forest performed better due to its ability to incorporate class_weight='balanced', addressing the underrepresented classes (3, 4, 8) more effectively than a single Decision Tree.

- Reduced Overfitting: While the Decision Tree likely overfit the training data, Random Forest’s ensemble approach averaged multiple trees, reducing overfitting and providing a more generalized performance.


