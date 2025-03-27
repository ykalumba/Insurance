# Insurance Company Benchmark (COIL 2000)

This studies patterns and insights from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/125/insurance+company+benchmark+coil+2000), and the main objective is to study whether a client predict will be interested in buying a caravan insurance policy and give an explanation why?.

## Data Preprocessing
- Tere are no Missing Values: all data fields are filled.
- Standardizing Numerical Features: data features were standardized to bring them to a similar scale.
    
## Model Training
Several regression models were trained and evaluated for their performance in predicting insurance premiums:
- K-means clustering
- Random Forest Regression

## Model Evaluation
The performance of each model was evaluated using the following metrics:
 - Baseline, Training and Test accuracy
   
## Discussion
Among the models evaluated, Logistic regression and Random Forest Regression (rfr), rfr demonstrated the best performance in terms of Training and Test accuracy. It is obsevrved that sociodemographics have more influence on hoe clients respond towards a specific product. 
