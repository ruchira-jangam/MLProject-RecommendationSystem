# Movie Recommendation System based on Reviews

This repository contains the code and data files for a data science project aimed at building a movie recommendation system that recommends movies to users based on their previous movie reviews. The project uses Python programming language and several libraries including pandas and Scikit-learn.

Recommender systems are among the most popular applications of data science today. They are used to predict the "rating" or "preference" that a user would give to an item. Almost every major tech company has applied them in some form. Amazon uses it to suggest products to customers, YouTube uses it to decide which video to play next on autoplay, and Facebook uses it to recommend pages to like and people to follow.

Recommender systems have also been developed to explore research articles and experts, collaborators, and financial services.

Recommender systems can be classified into Two types:

**Content-based recommenders:** suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person likes a particular item, he or she will also like an item that is similar to it. And to recommend that, it will make use of the user's past item metadata. A good example could be YouTube, where based on your history, it suggests you new videos that you could potentially watch.

**Collaborative filtering engines:** these systems are widely used, and they try to predict the rating or preference that a user would give an item-based on past ratings and preferences of other users. Collaborative filters do not require item metadata like its content-based counterparts.

Here I'm going to implement Content Based Filtering

**Dataset :**
The dataset used in this project consists of two files: db_5000_credits.txt and db_5000_movies.txt. The first file contains information on the cast and crew of movies, while the second file contains information on the movies themselves including their titles, release dates, and genres.
