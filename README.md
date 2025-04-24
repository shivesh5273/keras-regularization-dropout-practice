# Keras Regularization & Dropout Practice

This project showcases practical implementations of deep learning models using Keras, focusing on combating overfitting via **L1/L2 regularization** and **Dropout**. Three separate model types were explored across six tasks.

---

## 🔍 Project Breakdown

### ✅ Q1–Q3: Sentiment Classification (Movie Reviews)
- Implemented a binary classification model using `RMSprop` optimizer.
- Tested effects of L1 and L2 regularization.
- Compared dropout rates (25% vs 10%) to evaluate mitigation of overfitting.

### ✅ Q4–Q5: House Price Prediction
- Applied K-Fold cross-validation (K=3) using a regression model.
- Compared results with and without Dropout layers (p=0.5).

### ✅ Q6: Newswire Multi-Class Classification
- Trained a model with original 2-hidden-layer structure.
- Evaluated performance changes by testing 1-layer and 3-layer variants.

---

## 🗂 Files Included

| Filename                                           | Description                                 |
|----------------------------------------------------|---------------------------------------------|
| `keras-q1-q3-movie-review-classifier.html`         | Q1–Q3 solution with model training outputs  |
| `keras-q4-q5-house-price-predictor.html`           | Q4–Q5 solution with K-Fold validation       |
| `keras-q6-newswire-classifier.html`                | Q6 solution for multi-class classification |
| `keras-practice-questions.docx`                    | Problem statements for reference            |

---

## 🛠 Tools & Libraries

- Python 3.x  
- TensorFlow / Keras  
- Jupyter Notebook (HTML Exported)  
- Dropout, L1/L2 Regularization  
- RMSprop Optimizer

---

> Practicing model tuning techniques like Dropout and Regularization helps sharpen real-world deep learning intuition.
