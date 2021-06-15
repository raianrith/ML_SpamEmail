# Machine Learning Project: Spam Classifier

- Project aims to figure out the best Spam Email Classifying algorithm within the algorithms used based on misclassification rates and true negatives.
- Data set collected at Hewlett-Packard Labs, classifies 4601 e-mails as spam or non-spam. 

**Classifiers Used:**

- **Logistic Regression**
- **Linear Discriminant Analysis**
- **K Nearest Neighbour**
- **Decision Trees : Pruned Class Tree, Bagging, Random Forest**
- **Support Vector Machines: Linear, Polynomial, and Radial Kernels**

Amongst all the difference classifiers used, the bagging and support vector machine with linear kernel with very similar misclassification error rate. However based on the goal and purpose of the research, we would want the model which not only yields low misclassification error rate but also is the best in terms of not classifying non spam emails as spam emails. Hence, The bagging algorithm would be the optimal choice for the classification of spam and non-spam emails with a misclassification error rate of 12% (lowest among all models and approaches) and only 2 (lowest among all models and approaches) non spam emails being classified as spam emails. 

<img width="781" alt="Screen Shot 2021-06-14 at 7 07 53 PM" src="https://user-images.githubusercontent.com/61523138/121975372-185c3400-cd47-11eb-82fb-42d3f161c72e.png">

<img width="1354" alt="Screen Shot 2021-06-14 at 7 05 16 PM" src="https://user-images.githubusercontent.com/61523138/121975369-15f9da00-cd47-11eb-95f5-fcbe43679131.png">

