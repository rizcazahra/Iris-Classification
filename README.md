# Iris-Classification

The process of flower species classification involves splitting the Iris dataset into two parts: a training set comprising 80% of the data and a testing set with the remaining 20%. Using the training set, a classification model based on the K-Nearest Neighbors algorithm is developed. Once the model is trained, it is evaluated using the testing set, where unlabeled data is presented to the model for classification. By analyzing similarities with labeled instances in the training set, the model assigns species labels (Setosa, Versicolor, or Virginica) to the testing data. This approach outlines a systematic method for accurately categorizing new instances of Iris flowers into their respective species.

<img width="882" alt="image" src="https://github.com/rizcazahra/Iris-Classification/assets/84758353/4a84da2d-7220-447b-8bd7-099dc4c21e0d">


1. Importing Essential Libraries:
We commence by importing essential libraries such as Pandas, NumPy, and Matplotlib for data manipulation and visualization. Additionally, we import the KNeighborsClassifier from Scikit-learn, which serves as our primary tool for implementing the KNN algorithm.

2. Reading and Understanding the Dataset:
Before delving into modeling, it's crucial to comprehend the dataset at hand. We load the Iris dataset, a widely used benchmark dataset in machine learning, and conduct exploratory data analysis to grasp its structure and characteristics.

3. Splitting the Dataset:
To facilitate model training and evaluation, we partition the dataset into features (X) and target variables (y). Leveraging the train_test_split function, we divide the data into training and testing sets, ensuring unbiased evaluation of our model's performance.

4. The Essence of Data Normalization:
Normalization plays a pivotal role in preparing the data for modeling. Unlike standardization, which centers the data around zero with a standard deviation of 1, normalization scales the data to a range between 0 and 1. By bringing all features to a similar scale, normalization enhances the convergence rate of optimization algorithms and prevents dominance by features with larger magnitudes.

5. Unveiling K-Nearest Neighbors Algorithm:
At the heart of our classification task lies the KNN algorithm, a non-parametric method used for both classification and regression tasks. KNN operates under the principle of similarity, where the class of an unseen instance is determined by the classes of its k nearest neighbors. By selecting an appropriate value for k, we strike a balance between model complexity and generalization.

6. Model Training and Prediction:
With the data normalized and the KNN algorithm set up, we proceed to train our model using the training data. During training, the algorithm memorizes the feature vectors and their corresponding class labels. Subsequently, we utilize the trained model to predict the classes of the instances in the test set.

7. Evaluating Model Performance:
To gauge the effectiveness of our classifier, we compute the accuracy score, a metric that quantifies the proportion of correctly classified instances in the test set. A high accuracy score signifies the model's ability to generalize well to unseen data, indicating robust performance.

Conclusion:
In this article, we've embarked on a journey to unravel the intricacies of the KNN algorithm while applying it to classify the Iris flower dataset. By emphasizing the significance of data normalization, we've illustrated how preprocessing techniques can significantly impact model performance. As you delve deeper into the realm of machine learning, mastering algorithms like KNN equips you with the tools to tackle diverse classification tasks and unlock new insights from data.
