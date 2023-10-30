## Cab_Compnay_Driver_Attrition_Prediction

### Tasks Performed On This Project:
### Task: Data Overview:
- Reviewed the shape of the data (number of rows and columns).
- Examined data types of all attributes to understand their nature.
- Converted categorical attributes to the 'category' data type where necessary.
- Detected missing values in the dataset.
- Generated a statistical summary of the dataset to understand the central tendencies and distributions of numerical attributes.

### Univariate Analysis:
- Plotted distribution plots for all continuous variables to visualize their distributions.
- Created count plots for all categorical variables to understand their distributions.

### Bivariate Analysis:
- Explored relationships between important variables to identify potential correlations or patterns.

### Insights from EDA
- The dataset consists of entries and attributes.
- The dataset contains a mix of numerical and categorical attributes.
- Categorical attributes have been appropriately converted to the 'category' data type.
- Missing values were detected in some attributes; strategies for handling them were considered.
- The univariate analysis revealed the distribution of variables, and the bivariate analysis explored relationships between attributes.
- Comments on the range of attributes, presence of outliers, and distributions of variables were documented.

### Task: Data Preprocessing
During the Data Preprocessing phase, I performed the following tasks:

### KNN Imputation
- Utilized K-nearest neighbors (KNN) imputation to handle missing values in the dataset. This method imputes missing values by considering the values of the nearest neighbors.
### Feature Engineering
- Explored opportunities for feature engineering to create new variables or transform existing ones that could enhance the predictive models.
### Class Imbalance Treatment
- Investigated methods to address class imbalance, as it's essential to ensure that the model performs well on both classes (drivers who leave and those who stay).
### Standardization
- Standardized numerical features to ensure that they have a mean of 0 and a standard deviation of 1. This is a common preprocessing step for many machine learning algorithms.
### Encoding
- Performed encoding of categorical variables, converting them into a format suitable for model building.

### Task: Model Building
For the model-building phase, I implemented the following:

### Ensemble - Bagging Algorithm
- Developed an ensemble model using a bagging algorithm. Bagging helps to reduce overfitting and improve the model's generalization.
### Ensemble - Boosting Algorithm
- Constructed an ensemble model using a boosting algorithm. Boosting combines the predictions of multiple base models to create a stronger predictive model.

### Task: Results Evaluation
For model evaluation, I conducted the following:

### ROC AUC Curve & Classification Report
- Plotted the Receiver Operating Characteristic (ROC) curve and calculated the Area Under the Curve (AUC) to evaluate model performance.
- Generated a classification report, including metrics such as accuracy, precision, recall, and F1 score. This report also includes a confusion matrix to assess model performance further.

### Task: Actionable Insights & Recommendations
- Finally, I provided actionable insights and recommendations based on the results of the model evaluation. These insights can help Cab Company in addressing driver attrition and improving driver retention strategies.
