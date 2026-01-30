# Decision Tree Classification on Student Performance

This project demonstrates the complete data mining pipeline using a Decision Tree classifier on a synthetic student performance dataset.

## Dataset
- 100 student records
- Features: Age, Study_Hours, Attendance, Internal_Marks
- Target: Result (Pass / Fail)
- Dataset includes missing values and controlled noise for realism

## Steps Performed
1. Dataset generation using Python
2. Data exploration and preprocessing
3. Missing value handling
4. Feature normalization
5. Feature selection using Information Gain
6. Decision Tree classification
7. Model evaluation using Accuracy, Precision, Recall, and F1-score

## Files
- `generate_student_dataset.py` – Script to generate the dataset
- `student_performance_dataset.csv` – Generated dataset
- `decision_tree_student_performance.ipynb` – Full analysis and model training notebook

## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn

## How to Run
1. Run `generate_student_dataset.py` to create the dataset
2. Open and execute `decision_tree_student_performance.ipynb`