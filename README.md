# 📝 Text Document Classification using Naive Bayes

A simple Machine Learning project that classifies text documents into predefined categories using **Bag of Words (CountVectorizer)** and the **Multinomial Naive Bayes** algorithm. This project demonstrates the complete text classification workflow—from loading the dataset to predicting the category of custom user input.

---

## 📌 Project Overview

This project performs the following tasks:

- Loads a text dataset from a CSV file.
- Splits the dataset into training and testing sets.
- Converts text into numerical features using **CountVectorizer**.
- Trains a **Multinomial Naive Bayes** classifier.
- Evaluates the model using accuracy and a confusion matrix.
- Predicts the category of custom input text.

---

## 🚀 Features

- Text preprocessing using Bag-of-Words
- Multinomial Naive Bayes classifier
- Train/Test split for evaluation
- Model accuracy calculation
- Confusion Matrix visualization
- Custom text prediction

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
  - CountVectorizer
  - MultinomialNB
  - train_test_split
  - accuracy_score
  - confusion_matrix

---

## 📂 Project Structure

```
├── Classification of Text Documents.ipynb   # Jupyter Notebook
├── synthetic_text_data.csv                  # Dataset
└── README.md                                # Project documentation
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repository.git
```

Move into the project directory:

```bash
cd your-repository
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ▶️ Running the Project

1. Open the Jupyter Notebook:

```bash
jupyter notebook
```

2. Open:

```
Classification of Text Documents.ipynb
```

3. Run all cells in order.

---

## 📊 Machine Learning Workflow

```
Dataset
   │
   ▼
Train-Test Split
   │
   ▼
CountVectorizer
   │
   ▼
Multinomial Naive Bayes
   │
   ▼
Prediction
   │
   ▼
Accuracy & Confusion Matrix
```

---

## 📈 Model Evaluation

The notebook evaluates the model using:

- **Accuracy Score**
- **Confusion Matrix Heatmap**

These metrics help measure the classifier's performance on unseen data.

---

## 💡 Example Prediction

Input:

```text
I love artificial intelligence and machine learning
```

Output:

```text
The input text belongs to the "<Predicted Category>" category.
```

---

## 📚 Concepts Covered

- Natural Language Processing (NLP)
- Text Vectorization
- Bag of Words (BoW)
- CountVectorizer
- Multinomial Naive Bayes
- Model Training
- Model Evaluation
- Confusion Matrix
- Text Classification

---

## 🔮 Future Improvements

- TF-IDF Vectorization
- Data Cleaning & Text Preprocessing
  - Lowercasing
  - Stopword Removal
  - Stemming/Lemmatization
- Hyperparameter Tuning
- Support Vector Machine (SVM)
- Logistic Regression
- Larger Real-world Dataset
- Model Serialization using Pickle/Joblib
- Deploy with Flask or Streamlit

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a Pull Request

---

## 📄 License

This project is intended for educational and learning purposes.

---

## 👨‍💻 Author

**Prashant Kumar**

If you found this project helpful, consider giving the repository a ⭐.
