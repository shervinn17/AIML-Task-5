# Task 5: Decision Trees and Random Forests

## 📌 Objective
Learn and apply tree-based models for classification and regression using:
- **Decision Trees**
- **Random Forests**

## 🛠️ Tools & Libraries Used
- Python
- pandas
- scikit-learn
- matplotlib
- seaborn
- Graphviz (optional for .dot tree visualization)

## 📁 Dataset
The dataset used for this task is stored in a CSV file. It includes features for training and a target variable for classification. *(Replace 'target' with the actual column name in your dataset if different)*

## 🚀 Steps Performed

### 1. Data Loading & Preprocessing
- Loaded the dataset using `pandas`.
- Dropped missing values.
- Split the data into features (`X`) and target (`y`).
- Performed a train-test split (80% training, 20% testing).

### 2. Decision Tree Classifier
- Trained a `DecisionTreeClassifier` with a controlled `max_depth` to prevent overfitting.
- Visualized the decision tree using `matplotlib`.
- Evaluated model performance using accuracy score and classification report.

### 3. Random Forest Classifier
- Trained a `RandomForestClassifier` with 100 estimators.
- Compared accuracy with the decision tree.
- Identified important features using `feature_importances_`.

### 4. Model Evaluation
- Applied 5-fold cross-validation on both models.
- Reported mean cross-validation scores.

## 📊 Visualizations
- Decision tree plot.
- Bar chart of feature importances from the Random Forest.

## 📈 Results
| Model            | Test Accuracy | Mean CV Score |
|------------------|----------------|----------------|
| Decision Tree    | ✅ ~Your Score | ✅ ~Your Score |
| Random Forest    | ✅ ~Your Score | ✅ ~Your Score |

*(Update scores after running the script)*

## 📎 How to Run
1. Make sure the dataset CSV is in your working directory.
2. Replace `'target'` in the script with your actual target column.
3. Run the Python script in any environment (e.g., Jupyter Notebook, Colab, VS Code).
4. Install required packages if missing:

```bash
pip install pandas scikit-learn matplotlib seaborn
