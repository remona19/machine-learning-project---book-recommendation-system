# machine-learning-project---book-recommendation-system
In an era of information abundance, where readers are inundated with countless book options, the need for personalized recommendations has never been more critical. Collaborative filtering, a prominent technique in recommendation systems, offers a powerful solution to this challenge. Collaborative filtering operates on the principle of collective intelligence, leveraging the wisdom of the crowd to make personalized recommendations. Unlike content-based approaches that analyse book characteristics, collaborative filtering focuses on user behaviour, specifically user-item interactions. It identifies patterns and similarities among users based on their past interactions with books to predict preferences and generate recommendations. In the digital age where access to vast libraries of books is at our fingertips, personalized book recommendation systems have become essential tools for assisting readers in discovering content aligned with their interests. This report provides an overview of a book recommendation system implemented using collaborative filtering, highlighting its methodology, performance evaluation, and potential applications.

# Methodology
The method used to create a recommendation system is collaborative filtering and will use centred cosine similarity, cosine similarity, and k nearest neighbours. In giving a book recommendation to students in implementing the program code there are a number of steps that make all the data from borrowing the book into a matrix in the form of an array that will be calculated using an algorithm, in the second stage will be done the process of normalizing the ranking because in making book recommendations using borrowing data the number of books will continue to grow if borrowed by the same student and this makes the ranking scale erratic so that it needs normalization of ranks using centred cosine similarity, after the stage of normalization ranking is complete it will start using the cosine similarity algorithm to get the results of book rating. 

# Recommendation system
A recommendation system is a subclass of Information filtering Systems that seeks to predict the rating or the preference a user might give to an item. In simple words, it is an algorithm that suggests relevant items to users. Eg: In the case of Netflix which movie to watch, In the case of e-commerce which product to buy, or in the case of kindle which book to read, etc.

![image](https://github.com/remona19/machine-learning-project---book-recommendation-system/assets/147992703/3ae7c1c8-c7d0-46ce-a55f-ab0cae67c435)

# Collaborative based filtering
Recommending the new items to users based on the interest and preference of other similar users is basically collaborative-based filtering. This approach not only addresses the limitations of content-based filtering but also leverages user interactions, making it more robust. By focusing on the historical performance of users, this recommendation system can predict future preferences with greater accuracy.
There are 2 types of collaborative filtering:-

# •	User-Based Collaborative Filtering
The user profile is a vector that describes the user preference. During the creation of the user’s profile, we use a utility matrix that describes the relationship between user and item. From this information, the best estimate we can decide which item the user likes, is some aggregation of the profiles of those items.

![image](https://github.com/remona19/machine-learning-project---book-recommendation-system/assets/147992703/d03b5b26-7c7d-463e-8c98-a69288f97e13)

# •	Item-Based Collaborative Filtering
In a content-based recommendation system, we need to build a profile for each item, which contains the important properties of each item. For Example, If the movie is an item, then its actors, director, release year, and genre are its important properties, and for the document, the important property is the type of content and set of important words in it.

![image](https://github.com/remona19/machine-learning-project---book-recommendation-system/assets/147992703/e9aaa07e-d6af-431d-bf00-f0f22ae012b2)




