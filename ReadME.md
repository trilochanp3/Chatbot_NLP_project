# Chatbot for Intent Classification using NLP and Deep Learning

This project is a simple console-based chatbot that classifies user intents using natural language processing (NLP) and machine learning models. It uses NLTK for preprocessing, a neural network built with TensorFlow/Keras, and a backup SVM model using TF-IDF features.

---

## 📌 Features

- Tokenization, stop word removal, and lemmatization using NLTK
- Bag-of-Words vectorization + Deep Neural Network (Keras)
- TF-IDF + SVM (Scikit-learn) as a backup model
- JSON-based intent-response structure
- Confidence threshold logic to decide which model’s prediction to use
- Interactive console-based chatbot experience

---

## 🛠️ Technologies Used

- Python
- NLTK
- TensorFlow / Keras
- Scikit-learn
- NumPy
- JSON

---

## 📁 Files

- `code.ipynb` – Main notebook with all code from training to inference
- `data.json` – Intent patterns and responses
- `chatbot_m.h5` – Trained deep learning model
- `tokenizer_data.pkl` – Pickled objects: all words and label encoder

---
