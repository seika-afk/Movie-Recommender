# 🎬 Movie Recommender System (Content-Based)

This is a content-based movie recommendation system built using the TMDB 5000 dataset. It uses movie metadata like genres, cast, crew, and keywords to recommend similar movies.

## 🧠 Features

- Content-based filtering using movie descriptions
- NLP preprocessing to generate tags
- Cosine similarity to find similar movies
- Built with **Streamlit** for a clean web interface

## 📁 Dataset

Uses the following CSV files:
- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

Make sure they are in the same directory as the app.

## 🚀 Run Locally (Streamlit)

### 1. Install Python and Dependencies


```bash
pip install streamlit pandas numpy scikit-learn
```
Then Download this ,and put in a common folder , and under that folder ,using terminal ,Run:

```bash
streamlit run app.py
```
