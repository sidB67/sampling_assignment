## Sampling Assignment



## Tasks Performed :
1. Download the Creditcard_data.csv
2. Convert the dataset into balanced dataset using RandomOverSampling
3. Create five samples using different sampling techniques
4. Applied the five samples to 5 different models for prediciton
5. Determine Best model which provides best accuracy for which sample

## Sampling Technique Used
1. Simple Random Sampling
2. Systematic Sampling
3. Stratified Sampling
4. Cluster Sampling
5. Reservoir Sampling

## Models Used
1. LR - Logistic Regression
2. KNN - K Nearest Neighbor
3. RF - Random Forest Classifier
4. DT - Decision Tree Classifier
5. NB - Naive Bayes

## Performace Evaluation:
The cross validation results for the different samples with different models are mentioned below.
|      | Random | Systematic | Stratified | Cluster | Reservoir
|------|--------|------------|---------|------------|-----------|
| LR  | 0.92672 | 0.93965     | 0.90948   | 0.93965     |      0.89655      |
| KNN  | 0.88793 | 0.91379      | 0.92241  | 0.96982      |      0.88362     |
| RF  | 0.99137  | 0.99137     | 0.99137  | 0.99137     |        0.99137    |
| DT  | 0.96982  | 0.96982      | 0.99137   | 0.97413     |    0.97413        |
| NB  | 0.83620  | 0.84482     | 0.84051  | 0.95258    |      0.83620      |

Random Forest Classifier showed best accuracy for all the sampling techniques.
<br>
Stratified Sampling Technique is the best technique in this case but only marginally

## Submission by :
Name : Sidharth Bahl
<br>
Roll No : 102017016
