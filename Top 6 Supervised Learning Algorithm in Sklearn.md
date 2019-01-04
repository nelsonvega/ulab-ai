

What is **Supervised Learning**? .Well, It is  the Data mining process of inferring a function from labeled training data.

Confused? me too.

It is the task on which a functions is aproximated where an input X maps to an output Y.
Let me try again, You have an input X and an output Y, and you know both. For example, let’s say you have a data set with data about people who live in a zip code and their voting history. Using that information, you want to predict if a person in that zip code will be voting next year.

The whole point of supervised learning is about to create a function that maps the relationship between X(input) and Y( the output)

The goal is to approximate the mapping function so close that when you have a new data input, the output is correct.

Now, Supervised Learning can be grouped in:

#### Classification

A classification problem is when the output variable is a category that you want to attach to the input. For example email spam or not, organ donor or not.

#### Regression

Now regression is when things get interesting. Now you want to predict real values, not classifying the data.  
For example:

-   How much money allocated for a specific budget line item?
-   Predict economist growth of a state.
-   Salary estimation.

### Now, lets talk about implementation.

For that we are going to use scikit-learn:

What is it? Well scikit-learn, is a ML library written in Python and Cython that provide several of Machine Learning Algorithms.

Below you can find a few of them within the Supervise Learning domain

 ## Gaussian Naive Bayes (GaussianNB)

Naive Bayes classifier is based on the [Baye's theorem](https://en.wikipedia.org/wiki/Bayes%27_theorem)  with strong independence assumption between the features.

The theorem describe the probability of an event based on prior knowledge of conditions that might be related.

The classifier makes a very strong assumption on the shape of the data distribution. Any two features are independent given the output class. Because of this the output could be very bad.

For Example :
Taking a nap after eating turkey.
````LaTeX
P(nap)=Probability of taking a npa.
P(dinner) = Probability of eating turkey.
P(nap/turkey)=(P(turkey|nap) P(nap))/P(turkey)

$\frac{1}{4}^{\prime\prime}$
````

 	


## Decision Trees
##  Ensemble Methods (Bagging, AdaBoost, Random Forest, Gradient Boosting)
##  K-Nearest Neighbors (KNeighbors)
##  Stochastic Gradient Descent Classifier (SGDC)
##  Support Vector Machines (SVM)
##  Logistic Regression

