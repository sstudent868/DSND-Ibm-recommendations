# ibm-recommendations
Project for Data Science Nano-degree

## Introduction

For this project we look at the interactions that users have with articles on the IBM Watson Studio platform.

## Tasks

### Exploratory Data Analysis

### Rank Based Recommendations

We find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

### User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

### Matrix Factorization

Finally, we complete a machine learning approach to building recommendations. Using the user-item interactions, we build out a matrix decomposition. Using this decomposition, we get an idea of how well you can predict new articles an individual might interact with (spoiler alert - it isn't great). You will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.



## Files

1. Recommendations_with_IBM.ipynb - contains the main implementation and analysis
2. The `data` folder contains the dataset of interest
3. `project_tests.py` contain the tests
4. `.p` files are pickle files used in tests
