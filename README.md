**Fake News Detection Using Machine Learning**
📝 Description
This project is a simple machine learning application that detects whether a news headline is real or fake using Natural Language Processing (NLP) and a Logistic Regression classifier. It was built as part of an AI/ML internship project using Python and Scikit-learn, with a user-friendly interface created using Gradio for interactive testing.

🚀 Features
Binary classification of news headlines (Real or Fake)
Trained on a publicly available dataset from Kaggle
Uses TF-IDF for feature extraction
Built-in Gradio UI for live testing
Easily deployable and extendable

📁 Dataset
Source: Kaggle - Fake and Real News Dataset  (https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset/data)
Two CSV files:
True.csv: Real news articles
Fake.csv: Fake or misleading news


🎯 How It Works
Load and label real/fake news datasets.
Preprocess and vectorize the headline text using TF-IDF.
Train a Logistic Regression model on the vectorized text.
Launch a Gradio UI where users input a news headline and receive instant feedback on whether it's real or fake.

✅ Results
Accuracy: ~90%
Fast, lightweight, and interpretable
Can be extended using Deep Learning (LSTM, BERT) in the future

📌 Use Case
This model helps demonstrate the potential of machine learning in identifying misinformation and fake news. It is a lightweight and interpretable solution suitable for educational and research purposes.
