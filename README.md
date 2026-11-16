# Social Media Sentiment Analysis Using Machine Learning

## Project Overview
This project uses Machine Learning and Natural Language Processing (NLP) to analyze social media text and classify it into three sentiment categories: Positive, Negative, and Neutral.

## Objectives
- Analyze sentiment in social media comments.
- Process and clean textual data.
- Convert text into numerical features using TF-IDF.
- Train and evaluate multiple ML algorithms.
- Compare model performance.

## Dataset
The project uses Twitter and Reddit sentiment data.

Original sentiment labels:
- 1: Positive
- 0: Neutral
- -1: Negative

## Technologies Used
- Python
- Pandas and NumPy
- Scikit-learn
- NLTK
- Matplotlib and Seaborn
- TF-IDF Vectorization

## Machine Learning Algorithms
1. Multinomial Naive Bayes
2. Logistic Regression
3. Decision Tree Classifier

## Model Performance

| Model | Accuracy |
|---|---:|
| Naive Bayes | 72.39% |
| Logistic Regression | 89.85% |
| Decision Tree | 64.02% |

Logistic Regression achieved the highest accuracy of 89.85% in this experiment.

## Project Workflow
1. Dataset collection
2. Data preprocessing
3. Exploratory Data Analysis
4. Text cleaning
5. TF-IDF feature extraction
6. Model training
7. Model evaluation
8. Model comparison

## How to Run
Install dependencies:

`pip install -r requirements.txt`

Open the Jupyter Notebook and run the cells in sequence.

## Future Scope
- Develop a Streamlit web application.
- Analyze live social media data.
- Support additional languages.
- Improve model performance and generalization.

## Author
Ved Patil

Computer Science Engineering Student
