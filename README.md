# Book Recommender
A Collaborative Filter based deep learning recommender model which recommends books according to the taste of a user.

## Data
https://www.kaggle.com/zygmunt/goodbooks-10k

## Task
1. Identify users similar the current user by the ratings he/she has given on the same set of books.
2. Take the average rating of the books that similar users have read which the current user has not given.
3. Recommend those books with highest average rating to the current user.

## Model
1. Model each id(user, book) as an embedding that represent user's personal taste and book characteristics.
2. Embedding as a matrix of weights that can learn semantic relationship between users and books.
3. Keras Model containing Embedding and Dense layers to learn these weights and backpropagate through the user and books vectors.

