# 🎬 TMDb Movie Success Prediction

This project uses machine learning to predict whether a movie will be financially successful based on its metadata.

## 💡 Objective

Predict if a movie will earn more revenue than its budget using features like:

- Budget
- Popularity
- Runtime
- Genre (main genre)

## 📁 Dataset

The data is sourced from TMDb (The Movie Database) and consists of two merged files:  
- `tmdb_5000_movies.csv`  
- `tmdb_5000_credits.csv`  
Merged and cleaned into `tmdb_merged.csv`.

## 🧪 Methods

- **Data Cleaning:** Removing incomplete data and extracting main genres.
- **Feature Engineering:** One-hot encoding genres, creating binary target label `is_successful`.
- **Modeling:**
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
- **Evaluation:** Classification report, confusion matrix.

## 📊 Results

Both models performed reasonably well.  
KNN showed slightly better classification metrics with the selected features.

## 🔧 Tools & Libraries

- Python, Pandas, NumPy
- scikit-learn
- Seaborn, Matplotlib
