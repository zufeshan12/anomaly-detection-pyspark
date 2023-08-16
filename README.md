# anomaly-detection-pyspark
### Big Data Analysis - anomaly detection in synthetic financial data using PySpark | Comparative analysis of different ML algorithms in Spark ecosystem  
> A fraudulent transaction deviates significantly from an authentic transaction   and can simply be termed as an outlier or an anomaly in the world of transactions. Their behavior does not conform to the well-defined notion of  normal behavior.
Fraud Detection or anomaly detection has garnered a lot of traction in the recent times due to it’s evolving nature and mechanisms used by malicious users.

> Machine learning is progressively being employed to automate the process of anomaly detection through Supervised Learning (labeled observations – anomalous or authentic), Semi-Supervised Learning(only a portion of observations are labeled) as well as Unsupervised Learning (observations are unlabeled).

> Anomalies are very rare in the dataset. This means , we’ll be dealing with highly imbalanced datasets
> Patterns in fraudulent transactions differ significantly from those in normal observations
> Methods used to inject such behavior keep evolving as old ones get flagged by existing detection systems

> Due to the intrinsic sensitive nature of financial data, it’s difficult to find publicly available datasets that could be used to analyze fraudulent transactions. We aim to devise a method that can identify anomalous transactions from authentic ones as accurately as possible using Supervised Machine Learning algorithms (Logistic Regression, Tree-based algorithms and Ensemble Learning techniques to elevate performance)
As accuracy can be quite misleading here, we would be focusing on identifying False Negatives(when algorithm flags fraudulent transactions as authentic) as it is far more dangerous than False Positives(when algorithm flags authentic transactions as fraudulent, it can always be cross-verified). Hence, F1-score,F2-score is going to be our evaluation metric.
