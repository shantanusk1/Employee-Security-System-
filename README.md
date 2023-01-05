![image](https://user-images.githubusercontent.com/86349736/210834318-b47bdf9e-1a6f-4201-ad13-17da267c3669.png)



# Employee-Security-System-
 Building a new Employee Security System (Machine Learning)
You, as the Security analyst, at Stark Industries, have been tasked to build a new contactless employee check-in system. Currently the employees use a physical keycard for entry into the building like shown below. 

You have come up with a new idea that uses the employees smartphone and machine learning to provide a contactless system where when an employee enters the firm’s territory, his or her smartphone connects to the server and transmits data from the employee smartphone sensor data like the accelerometer's data. The server performs the calculations and determines this person as
one of the employees using Gait analysis. Essentially it compares the current pattern of the employee’s gait with the historial pattern and if there is a match, the doors automatically open for the employee to walk in. 

To test your idea, you have built a dataset of 30 employees and their daily activities here. Design and develop a system that will perform the gait analysis. 


Introduction:-

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. 
Each person performed six activities 

- WALKING

- WALKING_UPSTAIRS

- WALKING_DOWNSTAIRS

- SITTING

- STANDING 

- LAYING


## Technology Used :-

- Gait Analysis
- Machine Learning Models

                 1. Logistic Regression
                 
                 2. Decision Tree
                 
                 3. Gradient Boosting
                 
                 4. Long short-term memory (LSTM)





## Gait Analysis

Gait analysis is the systematic study of animal locomotion , more specifically the study of human motion, using the eye and the brain of observers, augmented by instrumentation  for measuring body movements, body mechanics  and the activity of the muscles.
Gait analysis is used to assess and treat individuals with conditions affecting their ability to walk. It is also commonly used in sports biomechanics to help athletes run more efficiently and to identify posture-related or movement-related problems in people with injuries.
The study encompasses quantification (introduction and analysis of measurable parameters of gaits), as well as interpretation, i.e. drawing various conclusions about the animal (health, age, size, weight, speed etc.) from its gait pattern.

In the given solution Gait Analysis is used to build a Employee Security System using gait analysis 
In the solution I have used new idea for the security and it is contactless .
It uses employee mobile phones and machine learning to provide the contactless system . When employee enters in  the company  or geofencing so their smartphones connects to the server and transmits data from the employee smartphone sensor data like the accelerometer's data.
The server performs the calculations using the gait analysis and it shows the current pattern of the employee using the historial patterns and is there is match in the walking style or any other activities then the doors automatically open for the employee to walk in. 




## Logistic regression

Logistic regression is one of the most popular Machine Learning algorithms, which comes under the Supervised Learning technique. It is used for predicting the categorical dependent variable using a given set of independent variables.
Logistic Regression can be used to classify the observations using different types of data and can easily determine the most effective variables used for the classification. The below image is showing the logistic function:

![image](https://user-images.githubusercontent.com/86349736/210829800-15678528-1bc3-46ac-9bb6-8a50c70109c3.png)

![image](https://user-images.githubusercontent.com/86349736/210829892-f791389e-b233-4f68-9d01-f4bd4ea02d43.png)





## Decision Tree

Decision Tree is a Supervised learning technique that can be used for both classification and Regression problems, but mostly it is preferred for solving Classification problems. 
It is a tree-structured classifier, where internal nodes represent the features of a dataset, branches represent the decision rules and each leaf node represents the outcome.

![image](https://user-images.githubusercontent.com/86349736/210830179-f9314fbd-1c27-428c-b6c9-af5bc9b95c25.png)

![image](https://user-images.githubusercontent.com/86349736/210830250-32ebdc31-b12c-4fae-902f-29fe6ba36d43.png)

![image](https://user-images.githubusercontent.com/86349736/210830316-487ef308-be09-4e2a-97f6-ead1dec3e75f.png)





## Gradient Boosting

Gradient Boosting is a popular boosting algorithm. In gradient boosting, each predictor corrects its predecessor’s error. In contrast to Adaboost, the weights of the training instances are not tweaked, instead, each predictor is trained using the residual errors of predecessor as labels.
Boosting is one of the popular learning ensemble modeling techniques used to build strong classifiers from various weak classifiers. It starts with building a primary model from available training data sets then it identifies the errors present in the base model. 
After identifying the error, a secondary model is built, and further, a third model is introduced in this process. In this way, this process of introducing more models is continued until we get a complete training data set by which model predicts correctly.


![image](https://user-images.githubusercontent.com/86349736/210830564-690bd6fd-f2c4-4aef-bde5-fa0f99045645.png)

![image](https://user-images.githubusercontent.com/86349736/210830626-119277d8-d69d-4e11-872e-8cc15cdca331.png)

![image](https://user-images.githubusercontent.com/86349736/210830674-782a6ccb-5a27-4483-805b-3a1e74491521.png)





## Long short-term memory (LSTM)

Long short-term memory (LSTM) is an artificial neura network used in the fields of artificial intelligence and deep learning. Unlike standard feedforward neural networks, LSTM has feedback connections. Such a recurrent neural network (RNN) can process not only single data points (such as images), but also entire sequences of data (such as speech or video). For example, LSTM is applicable to tasks such as unsegmented, connected handwriting recognition, speech recognition, machine translation,robot control,video games, and healthcare.

![image](https://user-images.githubusercontent.com/86349736/210831191-3f314c2d-2525-45ab-add0-f96fdac6b5ca.png)

![image](https://user-images.githubusercontent.com/86349736/210831278-bcc943a6-7e9a-4c6a-88ae-e94f0d507cd3.png)

![image](https://user-images.githubusercontent.com/86349736/210831329-136d549b-c290-46d3-aee5-a1ee5573782a.png)

![image](https://user-images.githubusercontent.com/86349736/210831374-47a248aa-3c30-4f7d-848c-70367561762e.png)

![image](https://user-images.githubusercontent.com/86349736/210831422-7d8a2413-46e0-4968-8e7e-84d9243e63c8.png)


This is the final accuracy of all Machine Learning Models . But this accuracy can be change when we run the model again and again.





















