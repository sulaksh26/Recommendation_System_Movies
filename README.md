# Recommendation_System_Movies
# 🎬 Movie Recommendation System – EDA + Content-Based Filtering
This project demonstrates how to explore movie rating data and build a simple content-based movie recommendation system using pandas, scikit-learn, and scipy.
# 📂 Dataset
The project uses two datasets:

ratings.csv: Contains user ratings for movies.

movies.csv: Contains movie titles and genres.

# 💡 Example Recommendation
Change the user_id in the script to get personalized suggestions:

'''

user_id = 104

recommend_movies_for_user(user_id, X, user_mapper, movie_mapper, movie_inv_mapper, k=10)

'''

Output:

Since you watched this, you might also like:

Out Cold (2001)

Pi (1998)

Hollywood Homicide (2003)

Hudsucker Proxy, The (1994)
