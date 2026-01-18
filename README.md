# Norm-Aware Book Recommendation System 📚✨

A collaborative filtering-based book recommendation system that goes beyond standard cosine similarity by incorporating both user rating patterns **and** rating magnitude. This approach provides more realistic, popularity-aware recommendations for datasets with highly varied ratings.

---

## 🚀 Features

- **Norm-Aware Similarity Metric:** Combines cosine similarity (pattern similarity) with rating magnitude to improve recommendation quality.
- **Top-K Recommendations:** Efficient pipeline to return the most similar books for a given query book or user.
- **Exploratory Data Analysis (EDA):** Insights into the dataset to understand rating distributions and patterns.
- **Comparison Analysis:** Observe differences between traditional cosine similarity and norm-aware similarity.

---

## 📊 Motivation

While cosine similarity effectively captures rating patterns, it ignores the magnitude of ratings. For example, two books could have the same rating pattern but vastly different rating values. Incorporating rating magnitude ensures that recommendations account for both similarity and popularity, resulting in more actionable suggestions.

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas & NumPy
- Jupyter Notebook
- Matplotlib / Seaborn (for EDA)
- Collaborative Filtering techniques

---

## 🗂️ Files in this Repository

- `book_recommendation.ipynb` – Jupyter Notebook containing the implementation, EDA, and recommendation pipeline.
- `book_ratings.csv` – Dataset of user, book, and ratings used for the project.
