Experiment data found [HERE](https://archive.ics.uci.edu/ml/datasets/Data+for+Software+Engineering+Teamwork+Assessment+in+Education+Setting).

Problem Statement:

- From a sample of student software engineering teams, too many failing grades were observed. We need to figure out the cause of this achievement gap by taking measured factors of each team’s process and determine why teams are performing below expectations and where they need attention.

Outcome:

- Given the list of factors that occurred for a student software engineering team in a given semester, we can predict how they will be graded.
- What type of model are we trying to build?
    - The dependent variable is a discrete nominal value, pass or fail that we can be represented using a binary or boolean.
    - In this case we will feed our data into a classifier model to help us predict if a team will pass or fail.

Data Collection, Understanding, Preparation:

- Identify missing values, outliers, anomalies
- Determine relationships and patterns
- Research a bit more how to deal with missing values
- Preparation:
    - Plan is probably to impute most of the missing values
    - Scaling, normalization, encoding categorical data
    - Split to training, validation, testing

Exploratory Data Analysis

- Gain insights and understand characteristics
- Visualize with graphs, descriptive statistics
- Identify correlations and other patterns
- This will help solidify a hypothesis and transition to feature engineering

Feature Engineering

- Hours
- Meeting hours
- Messages
- Commits
- Work hours

What kind of graph do I need here?

- Scatter plot doesn’t seem correct
- This isn’t exactly a probability so I don’t think box plot
- Pie chart
- Histogram
- Bar chart

Look for classifying algorithms

Feature scaling

Hypothesis, reject or fail to reject

PCA