# Probability

Probability is a branch of mathematics that deals with the likelihood of different outcomes in various situations. It is used to quantify the chance of a particular event happening.

if X, is the event,
P(X)= Number of favorable outcomes/Total number of possible outcomes

The basic formula for probability, P(X), is the ratio of the number of favorable outcomes to the total number of possible outcomes in the sample space. Here, favorable outcomes are those we are focusing on, and the sample space encompasses all conceivable outcomes. 

 When two events don't influence each other, their joint probability is the product of their individual probabilities.

 P(AB)=P(A)P(B), where A and B are independent
 
## Key Aspects of Probability

### Definition
Probability is a measure of the likelihood that an event will occur. It is quantified as a number between 0 and 1, inclusive, where 0 indicates impossibility and 1 indicates certainty.

### Basic Concepts
- **Trial**: Observing the event and recording the outcome. **Example:** Flipping a coin once and noting whether it lands on heads or tails.
- **Experiment**: An action or process that leads to one of several possible outcomes. **Example:** Flipping a coin 400 times, with each flip being a trial.
- **Outcome**: A possible result of an experiment. **Example:** Getting heads or tails on a single coin flip.
- **Event**: A set of outcomes of an experiment to which a probability is assigned. **Example:**  Getting heads 200 times out of 400 coin flips

- **Expected Values**: The expected value is like the average outcome you'd predict if you could repeat an experiment many times. It’s what you’d “expect” to happen on average.
For Categorical Value: E(X)= P(X) x n, where P(X) is probability of Event X occuing and n is the number of times trial is conducted
Expected value for numeric variables: E(X)= Σ P(X)i x ni, i=1 to n

- **Complements**: Complements are essentially the opposite of a given event. Denoted with an apostrophe, for example, A’ means “Not A”. Complements have specific properties:
    - They cannot happen at the same time.
    - Combined, they make up the entire set of possible outcomes.
    - The sum of their probabilities is always 1 (P(A) + P(A’) = 1).
    - The complement of a complement brings you back to the original event ((A’)’ = A).
For instance, if event A is drawing a spade from a deck of cards (P(A) = 0.25), then A’ is the event of drawing any card other than a spade (clubs, diamonds, or hearts). The probability of A’ is 1 minus the probability of A, which makes P(A’) = 0.75.

- **Probabilty Frequency Table**: A probability frequency table is a tool used in statistics to represent how often different outcomes occur in an experiment, and it also shows the probability of each of these outcomes. It's a simple way to visualize and understand the distribution of outcomes in a data set.
  
|Die Roll (Outcome) |	Frequency (Number of Times Rolled)|	Probability|
|1 | 10 | 10/60|
|2 | 9  |  9/60|
|3 | 11 | 11/60|
|4 | 10 | 10/60|
|5 | 10 | 10/60|
|6 | 10 | 10/60|

### Probability Models
There are two main types:
- **Classical Probability**: Assumes that all outcomes of an experiment are equally likely. The probability of an event is calculated as the number of favorable outcomes divided by the total number of possible outcomes.
- **Empirical (or Statistical) Probability**: Based on observations or experiments. It is calculated as the number of times an event occurs divided by the total number of trials or instances.

### Applications
Probability is used in a wide range of fields, including statistics, finance, gambling, science, and engineering. It helps in making predictions, evaluating risks, and making informed decisions under uncertainty.

### Rules of Probability
- **Addition Rule**: For mutually exclusive events, the probability of either event occurring is the sum of their individual probabilities.
- **Multiplication Rule**: For independent events, the probability of both events occurring is the product of their individual probabilities.

### Conditional Probability
The probability of an event given that another event has occurred. This concept is particularly useful in scenarios where the occurrence of one event affects the likelihood of another.

### Bayes' Theorem
A way of finding a probability when we know certain other probabilities. This theorem is particularly useful in fields like medical testing, finance, and machine learning.

Probability is a fundamental concept in many aspects of daily life, aiding in making predictions and understanding the likelihood of various events.
