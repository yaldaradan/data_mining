# Bag-of-Words Text Classification on [DATASET NAME]

**TL;DR:** Train and evaluate classic ML models (LogReg, NB, SVM, RF) on a bag-of-words / TF-IDF representation to classify [task, e.g., spam vs ham / sentiment].

## Why this project?
I wanted a solid baseline for NLP using interpretable features before jumping to deep models.

## Dataset
- Source: [link or brief source note]
- Size: [N rows], [# classes]
- Fields: [text_field], [label_field]

## Approach
- Preprocessing: lowercasing, tokenization, stopword removal, optional lemmatization
- Features: CountVectorizer / TfidfVectorizer (unigrams/bigrams)
- Models: Naive Bayes, Logistic Regression, Linear SVM, Random Forest
- Validation: 10-fold CV + held-out test split
- Metrics: accuracy, F1 (macro), confusion matrix

## Results (sample)
| Model | F1 (macro) | Accuracy |
|------|------------|---------|
| Logistic Regression | 0.91 | 0.92 |
| Linear SVM | 0.92 | 0.93 |

> Full tables and plots are in the notebook.
