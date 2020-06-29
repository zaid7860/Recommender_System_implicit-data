# Recommender_System_implicit-data
# Build recommender system using implicit data


# We have tons for library for explicit recommendation system but problem aries when we dont have explicit rating from user , This is my approach for solving one such problem

# There is no rating just sequence of challenges user has taken last 10 rounds, and we need to predict the next 3 round.


# I have used the library Turicreate by Apple which is blazzing fast and its very good for ios and mac deployment


# Metric is Mean Average Precision

![alt text](https://s3-ap-south-1.amazonaws.com/av-blog-media/wp-content/uploads/2018/03/Capture_eqn_2.jpg)







Your client is a fast-growing mobile platform, for hosting coding challenges. They have a unique business model, where they crowdsource problems from various creators(authors). These authors create the problem and release it on the client's platform. The users then select the challenges they want to solve. The authors make money based on the level of difficulty of their problems and how many users take up their challenge.

 

The client, on the other hand makes money when the users can find challenges of their interest and continue to stay on the platform. Till date, the client has relied on its domain expertise, user interface and experience with user behaviour to suggest the problems a user might be interested in. You have now been appointed as the data scientist who needs to come up with the algorithm to keep the users engaged on the platform.



The client has provided you with history of last 10 challenges the user has solved, and you need to predict which might be the next 3 challenges the user might be interested to solve. Apply your data science skills to help the client make a big mark in their user engagements/revenue.
