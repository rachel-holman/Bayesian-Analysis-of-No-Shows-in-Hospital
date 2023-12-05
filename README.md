# Bayesian Analysis of No Shows in Hospitals in 2016

We will be using Bayesian techniques to model no-shows for hospital appointments.

## Motivation:
When a patient “No Show’s” on a medical appointment, there are can be many negative consequences such as the resources/time are wasted on the scheduling process, along with delayed medical care, possibly impacting health.

## Goals:
Our goals for this project are to 1) Describe the uncertainty in “No Show” outcomes given specific demographic and medical information about a patient; 2) Evaluate the posterior probability distributions of the regression parameters for the predictor variables obtained from patients; and 3) Evaluate the model predictions and uncertainties in these predictions.

## Data:
The data can be found on kaggle: https://www.kaggle.com/datasets/raniahelmy/no-show-investigate-dataset/

## Approach:
We propose to use Bayesian logistic regression with Hamiltonian Monte Carlo and/or Hierarchical modeling based on neighborhood and will investigate:

1) a main effects model
2) a simpler model
3) a Bayesian model averaging approach

---

# Note: 

To run this code on your computer, first download the `noshowappointments-kagglev2-may-2016.csv` file from this repository or directly from the kaggle website linked above. 

Next, download the NoShowCode.ipynb file and ensure it is in the same folder at the data file. 

That's all! Now when you open this code in the software of your choice (Colab, Jupyter, Python, etc.) it should be able to be run smoothly!
