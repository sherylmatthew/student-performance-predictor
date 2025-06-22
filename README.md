# student-performance-predictor
# 🎓 Student Performance Predictor

This project uses **machine learning** to predict whether a student will **pass or fail** based on input features like study time, attendance, previous grades, parental education, and more.

It’s built using Python, pandas, and scikit-learn, and is beginner-friendly while covering the end-to-end ML pipeline.

---

## 🚀 Features

- Predicts academic performance (Pass/Fail)
- Uses classification models (Random Forest)
- Includes custom features like:
  - Parental education
  - Daily study hours
  - Internet access
  - Health and attendance %
- Optionally expandable to predict actual grades
- Ready to deploy with Streamlit or Colab

---

## 📂 Dataset

We used the [Student Performance Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams) from Kaggle. You can also simulate your own small dataset for testing purposes.

---

## 🧠 Machine Learning Pipeline

1. **Data Cleaning & Preprocessing**
2. **Feature Engineering**
3. **Model Training** (Random Forest Classifier)
4. **Evaluation** (Accuracy, F1-score)
5. **Prediction on New Data**

---

## 🧪 Sample Prediction

```python
# Predict for a new student
sample = pd.DataFrame([[0, 2.5, 0, 90, 2, 1, 1, 15, 14, 4]], columns=X.columns)
model.predict(sample)  # Output: Pass
