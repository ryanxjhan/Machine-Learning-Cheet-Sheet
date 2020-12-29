# Machine Learning Cheet Sheet

<a href="https://www.linkedin.com/in/ryanxjhan/" target="_blank">LinkedIn</a>

### Table of Contents

* [Classic Machine Learning Algorithms](#classic)
* [Bias-Variance Trade Off](#tradeoff)
* Interview Questions

<a name="classic"/>

### Classic Machine Learning Algorithms

| Algorithms          | Parameters                          | Pros | Cons |
| :------------------ | ----------------------------------- | ---- | ---- |
| Naive Bayes         | Smoothing factor                    |      |      |
| KNN                 | K value                             |      |      |
| Logistic Regression | Polynomial degree<br />Penalty term |      |      |
| Neural Networks     | Number of layers<br />Penalty term  |      |      |
| Decision Tree       | Tree depth                          |      |      |

<a name="tradeoff"/>

### Bias-Variance Trade Off

| Models        | Bias      | Variance      | Problem      |
| ------------- | --------- | ------------- | ------------ |
| Simple Model  | High Bias | Low Variance  | Underfitting |
| Complex Model | Low Bias  | High Variance | Overfitting  |

 ### Interview Questions

1. A data scientist is working on optimizing a model during the training process by varying multiple parameters. The data scientist observes that, during multiple runs with identical parameters, the loss function converges to different, yet stable, values. What should the data scientist do to improve the training process? (Reduce the batch size. Decrease the learning rate)