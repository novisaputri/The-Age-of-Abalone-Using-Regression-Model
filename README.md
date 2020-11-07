# The Age of Abalone Using Regression Model
Predicting the age of abalone from physical measurements using regression model in Python

Abalones also called ear shells or sea ears are sea snails found world wide. 

> The age of abalone is determined by cutting the shell through the cone, staining it, and counting the number of rings through a microscope (a boring and time consuming task). Other measurements, which are easier to obtain, are used to predict the age. Further information, such as weather patterns and location (hence food availability) may be required to solve the problem.

The data is from Kaggle(a platform for predictive modelling and analytics competitions), you can download it at https://www.kaggle.com/rodolfomendes/abalone-dataset

# Dataset
1.  Sex
    Contains three values: 'F', 'M' and 'I' they which correspond to 'Female', 'Male' and 'Infant' respectively.
2.  Length
    Continuous value in mm
3.  Diameter
    Continuous value in mm
4.  Height
    Continuous value in mm
5.  Whole weight
    Continuous value in gram
6.  Shucked weight
    Continuous value in gram
7.  Viscera weight
    Continuous value in gram
8.  Shell weight
    Continuous value in gram
9.  Ring
    Target column that you should predict
    
The researchers believed adding **1.5** to the ring count is a reasonable approximation of the abalones age. This complex method increases the cost and limits its popularity. Hence, researchers are interested in relating abalone age to variables like length, height and weight of the animal.
   
# Business Understanding
**PROBLEM** : The goal is to detect the age of abalone. If a reasonably accurate model could be found to predict the age of abalone, then the farmers would minimize the cost and customers would get the expected goods.

**QUESTION** : What is The Most Accurate Model to Predict The Age of Abalone ?

**MEASURE** : % accurate prediction of abalone age (Mean Absolute Error, Mean Square Error, Root Mean Square Error, R-Square)

I used 3 Regression Models and doing comparison:
1.  Linear Regression
2.  Random Forest Regression
3.  Decision Tree Regression

# References
ttps://www.kaggle.com/rodolfomendes/abalone-dataset

https://mpra.ub.uni-muenchen.de/91210/1/MPRA_paper_91210.pdf

https://becominghuman.ai/machine-learning-series-day-6-decision-tree-regressor-82a2e2f873a

https://www.quora.com/What-is-the-difference-between-scikit-learns-random-forest-classifier-and-random-forest-regressor
