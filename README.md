# Glass Classification Using Random Forest

## Objective

The objective of this project is to apply machine learning classification techniques to the Glass dataset. A Random Forest classifier is implemented and evaluated, along with Bagging and Boosting methods for comparison.

## Dataset

The **Glass dataset** contains chemical properties of glass samples. The features represent different chemical elements and properties of the glass, while the target variable represents the type/class of glass.

## Tasks Performed

### 1. Exploratory Data Analysis (EDA)

- Loaded and explored the Glass dataset.
- Examined the shape, data types, and summary statistics.
- Checked for missing values.
- Identified potential outliers and inconsistencies.
- Analyzed the distribution of the features.
- Studied relationships between variables using correlation analysis.

### 2. Data Visualization

The following visualizations were used to understand the dataset:

- Histograms
- Box plots
- Pair plots
- Correlation heatmap
- Class distribution plots

These visualizations helped identify feature distributions, relationships, correlations, and class imbalance.

### 3. Data Preprocessing

The following preprocessing steps were performed:

- Checked and handled missing values.
- Checked for duplicate records and inconsistencies.
- Encoded categorical variables if required.
- Applied feature scaling where appropriate.
- Analyzed and handled class imbalance.

### 4. Random Forest Classification

A Random Forest classifier was implemented using Scikit-learn.

Steps included:

- Dividing the dataset into training and testing sets.
- Training the Random Forest classifier.
- Making predictions on the test dataset.
- Evaluating the model performance.

The following metrics were used:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 5. Bagging and Boosting

Bagging and Boosting techniques were applied and compared with the Random Forest model.

#### Bagging

Bagging (Bootstrap Aggregating) trains multiple models independently on different bootstrap samples of the training data and combines their predictions.

#### Boosting

Boosting trains models sequentially, where each new model focuses more on the observations that were incorrectly predicted by previous models.

### Difference Between Bagging and Boosting

| Bagging | Boosting |
|---|---|
| Models are trained independently | Models are trained sequentially |
| Mainly reduces variance | Mainly reduces bias |
| Models can be trained in parallel | Models depend on previous models |
| Less sensitive to noisy data | Can be more sensitive to noisy data |
| Random Forest is an example | AdaBoost and Gradient Boosting are examples |

### 6. Handling Imbalanced Data

Class distribution was analyzed to identify imbalance in the target variable.

Possible techniques for handling imbalanced data include:

- Oversampling
- Undersampling
- SMOTE
- Class weights
- Using suitable evaluation metrics such as precision, recall, and F1-score

The appropriate approach was selected based on the distribution of the dataset.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Project Structure

```text
Glass-Classification-Using-Random-Forest/
│
├── Glass_Classification_Using_Random_Forest.ipynb
├── glass.xlsx
└── README.md
