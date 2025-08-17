Movie Recommendation System 🎬

This is my small ML project where I built a Movie Recommendation System.
It recommends movies similar to the one you select. For example, if you search for Gandhi, it will suggest 5 other related movies.

What I Did in This Project

I used the TMDB dataset from Kaggle (tmdb_5000_movies.csv and tmdb_5000_credits.csv).

I cleaned the data and picked only useful features: genres, keywords, cast, crew, and overview.

I merged them into one big column called tags.

Then I converted tags into numbers using CountVectorizer and found similarity between movies using Cosine Similarity.

I saved the processed data and similarity matrix using pickle.

Finally, I created a Streamlit app where you can type a movie name and it shows you top 5 similar movies with posters.

Tools & Libraries I Used

Python

Pandas, Numpy (for data cleaning)

Scikit-learn (for CountVectorizer + Cosine Similarity)

Pickle (to save models)

Streamlit (to build the app)

TMDB API (to get movie posters)