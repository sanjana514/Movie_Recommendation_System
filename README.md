# LLM_Based_Movie_Recommendation_System
# 🎬 Movie Recommendation System

A Machine Learning project that recommends movies similar to a user's selected movie using **Content-Based Filtering**. The system analyzes movie metadata such as genres, keywords, cast, crew, and overview to find similar movies based on **Cosine Similarity**.

## 📌 Features

* Content-Based Movie Recommendation
* Data Cleaning & Preprocessing
* Feature Engineering
* Text Vectorization using **CountVectorizer**
* Similarity Calculation using **Cosine Similarity**
* Top Movie Recommendations based on user input

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* NLTK

## 📂 Dataset

The project uses the **TMDB 5000 Movie Dataset**:

* `tmdb_5000_movies.csv`
* `tmdb_5000_credits.csv`

## 🚀 Project Workflow

1. Load and merge movie datasets.
2. Clean and preprocess the data.
3. Create movie tags using genres, keywords, cast, crew, and overview.
4. Convert text into vectors using **CountVectorizer**.
5. Calculate movie similarity using **Cosine Similarity**.
6. Recommend the most similar movies based on the selected movie.

## ▶️ How to Run

```bash
git clone https://github.com/sanjana514/Movie_Recommendation_System.git
cd Movie_Recommendation_System
pip install pandas numpy scikit-learn nltk
jupyter notebook
```

Open **Movie_Recommendation_System_Final.ipynb** and run all cells.

## 📁 Repository Contents

* `Movie_Recommendation_System_Final.ipynb` – Complete implementation
* `tmdb_5000_movies.csv` – Movie dataset
* `tmdb_5000_credits.csv` – Credits dataset

## 📌 Output

The notebook demonstrates the complete recommendation process with sample inputs and outputs, showing movies that are most similar to the selected title.

## 👩‍💻 Author

**Sanjana**

GitHub: https://github.com/sanjana514/Movie_Recommendation_System
