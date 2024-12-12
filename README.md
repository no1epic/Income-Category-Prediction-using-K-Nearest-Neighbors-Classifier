# Predicting Income Categories Using KNN

## Overview
This project predicts individuals' income categories (low or high) based on demographic and socioeconomic factors using the K-Nearest Neighbors (KNN) algorithm. It involves comprehensive data cleaning, exploratory data analysis (EDA), preprocessing, and evaluation of the model's performance.

## Objectives
- Predict whether an individual's income is below or above $50,000.
- Explore key demographic and socioeconomic factors influencing income levels.
- Evaluate model performance using accuracy, confusion matrix, and classification report.

## Dataset
The dataset includes features such as:
- **Age**
- **Work Class**
- **Education**
- **Marital Status**
- **Occupation**
- **Race**
- **Gender**

## Process
### 1. Data Cleaning and EDA
- Checked for missing values and analyzed descriptive statistics.
- Visualized feature distributions using box plots.
- Removed outliers using the Interquartile Range (IQR) method.

### 2. Feature Engineering
- Created the `Income_Category` column to classify income into 'low' and 'high' categories.

### 3. Data Preprocessing
- Encoded categorical variables using `LabelEncoder`.
- Standardized numerical features using `StandardScaler`.

### 4. Model Training
- Split data into training and testing sets.
- Applied the KNN algorithm with varying `k` values.
- Evaluated performance using accuracy score, confusion matrix, and classification report.

## Tools and Technologies
- **Python Libraries:**
  - `pandas` and `numpy` for data manipulation.
  - `seaborn` and `matplotlib` for visualization.
  - `scikit-learn` for preprocessing and modeling.
- **Algorithms:**
  - K-Nearest Neighbors (KNN).

## Results
- Identified significant factors influencing income levels.
- Evaluated model performance with optimal `k` values.
- Visualized classification results and metrics.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn ydata-profiling
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook ALY6020_Sahilgawande_Week1_assignmnet_2023.ipynb
   ```

## Usage
1. Load the dataset and perform EDA.
2. Preprocess the data by encoding and scaling features.
3. Train and test the KNN model with different `k` values.
4. Evaluate and interpret model performance.

## Contributing
Contributions are welcome! Feel free to submit a pull request or suggest improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Author
**Sahil Gawande**

For any inquiries, please contact me directly.
