# Fake-News-Prediction

=> This project focuses on classifying news articles as either reliable or unreliable using a dataset with titles, authors, and text content. Key steps include:

1. Dataset Overview:
- train.csv contains news articles labeled as reliable (0) or unreliable (1).
- test.csv lacks the label, used for testing.

2. Data Preprocessing:
- Missing values filled with empty strings.
- A new "content" column merges title and author.

3. Text Preprocessing:
- Porter Stemming applied to reduce words to root forms.
- Non-alphabetic characters removed; stopwords filtered out.

4. Data Transformation:
- TF-IDF Vectorizer converts text into numerical features.

5. Model Training:
- Logistic Regression model trained on 80-20 split of data.

6.Evaluation:
- Model accuracy is calculated after training.

=> Conclusion:
- The Logistic Regression model successfully classifies news articles, proving effective in detecting unreliable news based on textual data.
