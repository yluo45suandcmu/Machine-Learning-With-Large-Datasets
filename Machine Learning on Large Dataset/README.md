# Machine Learning on Large Dataset

## Project Summary

In this part of the homework, I perform exploratory data analysis (EDA) and data cleaning, and then train models with the original features. You will then perform feature engineering similar to what we did in
Homework 1 (TF-IDF and Bag-of-Words), and then train models with these new features.

3.1 Setting up EMR and Spark
With our data ready in S3, it’s now time to configure and create an EMR (Elastic MapReduce) cluster and run Spark, starting from the notebook hw4.ipynb. Include at least Hadoop, JupyterHub, and Spark in your
cluster software configuration. Set maximizeResourceAllocation to true (see here) in software settings.
Select your EC2 key pair.
Then, log in to jupyter (learn about login credentials here), upload your notebook, and start working!
Again, cost management is key. Because we might be running a cluster of machines, this could easily blow up your budget. We recommend using at most 1 Driver and 1 Core of type m5.xlarge while developing and debugging on a subset of MSD. You could scale this up to multiple Core workers when doing the final run. You may also utilize AWS spot instances to save cost during development.
