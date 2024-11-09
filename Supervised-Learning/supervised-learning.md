# Machine Learning Course by Andrew Ng

## What is Machine Learning?
Field of study that gives computers the ability to learn without being explicitly programmed.  
*– Arthur Samuel (1959)*

## Machine Learning Algorithms
- Supervised Learning (used most in many real-world applications)
- Unsupervised Learning

### Supervised Learning
Supervised learning refers to algorithms that learn mappings from `x` to `y`. The key characteristic of supervised learning is that it trains on examples with correct answers, where `y` is the label corresponding to input `x`. By seeing pairs of input `x` and desired output `y`, the algorithm eventually learns to predict the output label accurately from just the input.

<img src="https://github.com/sharjeelbhullar/Machine-Learning-Specialization/blob/main/I-O%20Mapping.png">

In these applications, you first train your model with examples of inputs `x` and the correct labels `y`. Once the model has learned from these `(x, y)` pairs, it can take a new input `x` it has not seen before and try to predict the appropriate output `y`.

For instance, by using data on house sizes and prices, a model can predict the price of a house of any given size by analyzing similar examples. If a person chooses a house of 750 square feet, the model can estimate the price by comparing it with prices of other houses of similar sizes. This process is an example of a specific type of supervised learning called regression, where we try to predict a numerical value, such as house prices in this case.
