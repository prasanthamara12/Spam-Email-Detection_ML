Email Spam Detection using Machine Learning
Project Overview
This project implements an Email Spam Detection system using Machine Learning and Natural Language Processing (NLP). The model classifies emails as either Spam or Not Spam based on their content. It helps automate email filtering and improve communication security.
Features
Email text preprocessing
TF-IDF feature extraction
Spam and non-spam classification
Model training using Multinomial Naive Bayes
Accuracy evaluation and performance metrics
Prediction on custom email messages
Technologies Used
Python
Google Colab
Pandas
NumPy
Scikit-learn
Matplotlib
Dataset
The project uses an email dataset containing:
text: Email content
spam: Target label (0 = Not Spam, 1 = Spam)
Machine Learning Workflow
Data Collection
Data Preprocessing
Feature Extraction using TF-IDF
Train-Test Split
Model Training using Naive Bayes
Model Evaluation
Email Prediction
Model Used
Multinomial Naive Bayes
This algorithm is widely used for text classification tasks and provides high accuracy for spam detection problems.
Results
The model achieves high classification accuracy by learning patterns from email text and identifying spam messages effectively.
Project Structure
Email-Spam-Detection/
│
├── emails.csv
├── spam_detection.ipynb
├── spam_model.pkl
├── vectorizer.pkl
└── README.md
Installation
pip install pandas numpy scikit-learn matplotlib
Run the Project
python spam_detection.py
or execute the notebook in Google Colab/Jupyter Notebook.
Sample Prediction
Input:
Congratulations! You have won a free iPhone.
Output:
SPAM EMAIL
Future Enhancements
Deploy as a web application using Flask or Streamlit
Add support for multilingual emails
Compare multiple machine learning algorithms
Integrate deep learning models for improved accuracy
Author
Amara Prasanth Kumar
B.Tech – Electronics and Communication Engineering (ECE)
