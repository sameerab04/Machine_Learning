# CS1675: Introduction to Machine Learning

Introductory machine learning course which gives an overview of many models and algorithms used in modern machine learning, including linear models, multi-layer neural networks, support vector machines, density estimation methods, bayesian belief networks, clustering, ensemble methods, and reinforcement learning. 

## Assignments

| Homework | Overview |
| ------ | ------ |
| HW1 | This assignment steps through programming syntax with ggplot2 and introduces the formula interface with the lm() function. The grammar of graphics can help create meaningful visualizations which communicate Exploratory Data Analysis (EDA) findings. Visualizations will provide context to the model results, which might be opaque and difficult to interpret. In this assignment you will demonstrate basic syntax, go through a detailed EDA of a common data set, and then begin to work through the syntax of fitting a model.
| HW2 | This assignment introduces training and comparing models with the caret package. You will demonstrate a majority of the steps in predictive modeling applications. You will apply those actions to a simplified regression example. You will then work with a binary classification problem, focusing on calculating confusion matrix metrics from given model predictions.

| HW3 | In the previous assignment, you calculated important binary classification performance metrics by hand. You will now use existing functions from the caret and yardstick packages to train and assess the performance of multiple binary classifiers. The resampling and model evaluation will be managed by the
caret package. You will consider several performance metrics and study what those metrics tell you about the model behavior. You will use functions from the yardstick package to help visualize the ROC curve. Please download and install yardstick before starting the assignment. You can do so directly or by downloading and installing tidymodels .
After evaluating performance based on Accuracy and the ROC curve you will also compare performance based on the calibration curve. You will first create the calibration curve manually before using existing functions from caret to generate the calibration curve automatically.

| HW4 | This assignment focuses on the mathematics of likelihoods, priors, and posterior distributions. You will work with the Binomial likelihood and a Beta prior throughout this assignment.

| HW5 | This assignment provides practice working with and manipulating Gaussian distributions. You will calculate derivatives, perform change-of-variable transformations, and also start working with the optim() function.

| HW6 | This assignment works through the details estimating an unknown mean, /mu/ , and unknown noise, /sigma/ , for a Gaussian likelihood. You will practice visualizing the log-posterior, work through the mathematics of the estimation process, and ultimately use the Laplace Approximation to approximate the joint posterior distribution on /mu/ and /sigma/ given observations. This assignment include programming and derivations.

| HW7 | This homework assignment is focused on working with linear models. You will fit, make predictions with, and assess linear model performance. You will calculate errors on training and test sets, as well as evaluate performance using the log-Evidence (log marginal likelihood).
| HW8 | This homework assignment is focused on model complexity and the influence of the prior regularization strength. You will fit non-Bayesian and Bayesian linear models, compare them, and make predictions to visualize the trends. You will use multiple prior strengths to study the impact on the coefficient posteriors and on the posterior predictive distributions.
You are also introduced to non-Bayesian regularization with Lasso regression via the glmnet package. If you do not have glmnet installed please download it before starting the assignment.

| Midterm | This midterm tests your understanding of the concepts, math, and programming required to learn distributions from data. You are required to perform a mixture of derivations and programming to solve the questions on the exam. Read the problem statements carefully.

| HW10 | This assignment focuses on the architecture of single hidden layer feedforward neural networks. You will practice calculating hidden units and neural network responses for a regression task. You will gain experience understanding the interaction between the hidden unit and output layer parameters. You will fit a regression neural network to data by minimizing the sum of squared errors (SSE), and tune the number of hidden units via a hold-out test set. Lastly, you will use caret to manage the resampling and tuning of a neural network for you.

| Final | Final project dealing with a real life example involving data exploration, implementing both regression and classification models and outcome interpreation to help determine which customers of PPG are the most difficult to predict in terms of time spent helping customers and achieving sales goals.  
