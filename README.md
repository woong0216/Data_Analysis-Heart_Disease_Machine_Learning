# Data_Analysis-Heart_Disease_Machine_Learning
## Propose
- We want to identify significant variables for heart disease.
- We want to classify heart disease patients into segments.

## Dataset

![Data Information](https://user-images.githubusercontent.com/63955072/122847794-4d6a1700-d343-11eb-87eb-0d44b0f2c628.png)

## Method
- Entropy
> Average value of 30 turns <br/>

![Entropy](https://user-images.githubusercontent.com/63955072/122848513-9ec6d600-d344-11eb-87d9-12dba4e2d1fa.PNG)

- Gini
> Average value of 30 turns <br/>

![Gini](https://user-images.githubusercontent.com/63955072/122848587-cf0e7480-d344-11eb-8690-317ec2ed244a.PNG)

- Gain Ratio
> Average value of 30 turns <br/>

![Gain Ratio](https://user-images.githubusercontent.com/63955072/122848594-d6ce1900-d344-11eb-817b-57153b06a0df.PNG)

- One Sided DT
> Setting max depth <br/>

![One Sided DT 1](https://user-images.githubusercontent.com/63955072/122848704-139a1000-d345-11eb-9d5a-c882087f7a9e.PNG)

> Draw One Sided Decision Tree <br/>

![One Sided DT 2](https://user-images.githubusercontent.com/63955072/122848811-3d533700-d345-11eb-9279-2ed2e709fcfa.PNG)

## Analysis
- Gini had the highest accuracy for classification.
- The root node was considered to be the most important because it showed the most cp.
- The largest group was often divided into two components: cp (chest pain) and ca (vascular number).
- In the mid-50s, it is most frequent to be divided by age at the baseline of whether or not heart disease exists.
- test set accuracy: Gini > One Sided Decision > Entropy > Gain Ratio

## Conclusion
- It can visually identify a group of people with or without heart disease.
- The distribution can be determined by the intensity of the color.


