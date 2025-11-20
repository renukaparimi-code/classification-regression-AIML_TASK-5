# classification-regression-AIML_TASK-5
This task explores tree-based machine learning models for both classification and regression.   Using a custom dataset on mental health and social media behavior, the goal is to:

- Train a Decision Tree Classifier  
- Visualize the tree structure  
- Analyze overfitting & control depth  
- Train a Random Forest Classifier  
- Compare their performance  
- Interpret feature importance  
- Evaluate using cross-validation  

---

## 📂 Dataset Used
**Mental_Health_and_Social_Media_Balance_Dataset.csv**

Features include:

- Age  
- Gender  
- Daily Screen Time  
- Sleep Quality  
- Stress Level  
- Exercise Frequency  
- Social Media Platform  
- Happiness Index  

The target label for classification:
- `Happiness_Level` (Low / Medium / High)

---

## 🧠 What I Did

### ✔ Data Preprocessing
- Cleaned column names  
- Converted happiness score into categories  
- Encoded categorical features (Gender, Platform, etc.)  
- Split data into training and testing sets  

---

## 🌳 Decision Tree Classifier
- Trained a tree classifier  
- Visualized the model using Graphviz  
- Analyzed overfitting  
- Retrained with `max_depth=4`  

### **Metrics**
- Accuracy  
- Classification report (Precision / Recall / F1)  

---

## 🌲 Random Forest Classifier
- Trained with 100 trees  
- Compared accuracy with Decision Tree  
- Extracted feature importances  

---

## 🔍 Cross-Validation
Used 5-fold CV to measure reliability of the Random Forest model.

---

## 📊 Results (example)
- Decision Tree Accuracy: ~0.70  
- Decision Tree (max_depth=4) Accuracy: ~0.74  
- Random Forest Accuracy: ~0.80  
- Cross-Validation Mean Score: ~0.78  

(Random results depend on the dataset distribution.)

---

## 🛠 Tools Used
- Python  
- Google Colab  
- Pandas  
- Scikit-Learn  
- Graphviz  

---

