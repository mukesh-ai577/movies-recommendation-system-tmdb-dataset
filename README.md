# movie-recommender-system-tmdb-dataset

A content-based movie recommender system using cosine similarity.

## 🚀 Features

- 🎬 Movie recommendations based on content similarity
- 🔍 Uses cosine similarity to find similar movies
- 🎞️ Movie posters fetched using TMDB API
- 🌐 Interactive web interface using Streamlit
- 🐍 Built using Python

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- TMDB API

## 📌 How It Works

The system recommends movies similar to the movie selected by the user.

It uses movie metadata to calculate similarity between movies using **Cosine Similarity**.

```text
Movie Selection
      ↓
Movie Metadata
      ↓
Feature Extraction
      ↓
Cosine Similarity
      ↓
Similar Movies
      ↓
Movie Posters