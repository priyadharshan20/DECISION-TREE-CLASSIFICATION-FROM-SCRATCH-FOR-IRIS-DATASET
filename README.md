# DECISION-TREE-CLASSIFICATION-FROM-SCRATCH-FOR-IRIS-DATASET

In the decision-tree.ipynb python notebook I have implemented Decision Tree Machine Learning algorithm from scratch without using any ML frameworks or libraries.

Here I have implemented the decision tree classification algorithm to classify the plant species using the given features in the iris dataset.

The features are 
 1. SepalLengthCm
 2. SepalWidthCm
 3. PetalLengthCm
 4. PetalWidthCm

The Target Variable is 'Species' 

The Iris dataset has 150 rows which are splitted into testing(20%) and training(80%) subsets.

Prerequisites:
 1. Knowledge on Tree data structure and its implementation.
 2. knowledge on the concept of decision tree.

The functions involved are explained below

**1. **def entropy(variables) :****

    This function is used to calculate the entropy of a given list of categorical variables. Entropy is a measure of the uncertainty or randomness in a set of data that is how much different classes are present in that list.
      
    If entropy is zero it means that the list is homogeneous( or list with one single class).If entropy is above zero it means the list is heterogeneous (or list has many different class). Usually the entropy value is between 0 and 1.
             
    The formula for entropy calculation is 
        
    The entropy 𝐻 of a set of data 𝑆 with 𝑛 different possible values (categories) is calculated using the formula:
        
    𝐻(𝑆) = −∑𝑖=1 to 𝑛 𝑝𝑖 * log2(𝑝𝑖)
         
    where pi = no. of ith value in the dataset / total no. of values in the dataset.
  
