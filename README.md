# MovieScout
An online tinder like interface for movie recommendation. Uses Content based and collaborative filtering to generate recommendations on the go.

# Features

-  User authentication (Flask backend)
-  Hybrid recommendation engine (collaborative + content-based)
-  Uses MovieLens for training, TMDB for metadata (poster, release date, etc.)
-  React frontend with Context API for state sharing
-  Pages: Login, Signup, Home, Liked Movies, and more

# Tech Stack

- **Frontend**: React, Context API
- **Backend**: Flask, Flask-JWT-Auth
- **ML Model**: Hybrid recommender using MovieLens data. SVD for collaborative filtering
- **Database/API**: TMDB API for movie metadata
