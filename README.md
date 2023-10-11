# OpeninApp_assignment_AIMl
## Task:
Create a Hinglish translation from English text. The text should sound natural and also
convert all the difficult words and phrases in English to Hinglish. This converted text should
be easy to understand for even a non-native Hindi speaker.
We have attached below the statements that are required to be used for this assignment.
1. Definitely share your feedback in the comment section.
2. So even if it's a big video, I will clearly mention all the products.
3. I was waiting for my bag.
## Code:
1.First import all the required libraries.
![1](https://github.com/yeshwanth1110/OpeninApp_assignment_AIMl/assets/94799982/4204897f-50a1-4017-b985-a4b3f9396e43)
2.In this task we are performing translation three time, firstly we convert the string taken as input to hindi using translator library and later we identify the nouns and make a list of the nouns and also identify stopwords in hindi.
3.After that, we replace the nouns from the translated sentence with english translations of the respective nouns using openai.
4.Finally print the final translated sentence
Note: The openai API used here has a limited access hence if the openai fails to run change the API link.
![2](https://github.com/yeshwanth1110/OpeninApp_assignment_AIMl/assets/94799982/cb526776-9d9c-420a-a5b3-0f12f5d44f0b)
## Output for first statment:
statment:Definitely share your feedback in the comment section.
![first case](https://github.com/yeshwanth1110/OpeninApp_assignment_AIMl/assets/94799982/24185b6e-d6bd-48ab-abfe-7576641ea233)
## Output of second statment:
statment: So even if it's a big video, I will clearly mention all the products.
![second case](https://github.com/yeshwanth1110/OpeninApp_assignment_AIMl/assets/94799982/3bad3d22-fa96-4861-b267-65510913a8f2)
## Output of third statment:
statment: I was waiting for my bag.
![4](https://github.com/yeshwanth1110/OpeninApp_assignment_AIMl/assets/94799982/4cba36a0-c85e-44cc-85d8-c1fe58a68fff)
Note: As the model was developed in a short timeline it was trained on a limited data and yet attained this accuracy.
