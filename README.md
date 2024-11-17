# neural-network-challenge-2
 Mod19 Challenge
Module 19 Challenge
Due Oct 30 by 11:59pm Points 100 Submitting a text entry box or a website url Attempts 0 Allowed Attempts 4
Background
You are tasked with creating a neural network that HR can use to predict whether employees are likely to leave the company. Additionally, HR believes that some employees may be better suited to other departments, so you are also asked to predict the department that best fits each employee. These two columns should be predicted using a branched neural network.

Files
Download the following files to help you get started:

Module 19 Challenge filesLinks to an external site.

Before You Begin
Before starting the Challenge, be sure to complete the following steps:

Create a new repository for this project called neural-network-challenge-2. Do not add this Challenge assignment to an existing repository.

Clone the new repository to your computer.

Inside your local Git repository, add the starter file attrition.ipynb from your file downloads.

Push these changes to GitHub.

Upload attrition.ipynb to Google Colab and work on your solution there.

Make sure to periodically download your file and push the changes to your repository.
Instructions
Open the starter file in Google Colab and complete the following steps, which are divided into three parts:

Part 1: Preprocessing
Import the data and view the first five rows.

Determine the number of unique values in each column.

Create y_df with the attrition and department columns.

Create a list of at least 10 column names to use as X data. You can choose any 10 columns you’d like EXCEPT the attrition and department columns.

Create X_df using your selected columns.

Show the data types for X_df.

Split the data into training and testing sets.

Convert your X data to numeric data types however you see fit. Add new code cells as necessary. Make sure to fit any encoders to the training data, and then transform both the training and testing data.

Create a StandardScaler, fit the scaler to the training data, and then transform both the training and testing data.

Create a OneHotEncoder for the department column, then fit the encoder to the training data and use it to transform both the training and testing data.

Create a OneHotEncoder for the attrition column, then fit the encoder to the training data and use it to transform both the training and testing data.

Part 2: Create, Compile, and Train the Model
Find the number of columns in the X training data.

Create the input layer. Do NOT use a sequential model, as there will be two branched output layers.

Create at least two shared layers.

Create a branch to predict the department target column. Use one hidden layer and one output layer.

Create a branch to predict the attrition target column. Use one hidden layer and one output layer.

Create the model.

Compile the model.

Summarize the model.

Train the model using the preprocessed data.

Evaluate the model with the testing data.

Print the accuracy for both department and attrition.

Part 3: Summary
Briefly answer the following questions in the space provided:

Is accuracy the best metric to use on this data? Why or why not?

What activation functions did you choose for your output layers, and why?

Can you name a few ways that this model could be improved?

Hints and Considerations
Review previous modules if you need help with data preprocessing.

Make certain that your training and testing data are preprocessed in the same ways.

Review Day 3 of this module for information on branching neural networks.

Requirements
Preprocessing (40 points)
Import the data. (5 points)

Create y_df with the attrition and department columns. (5 points)

Choose 10 columns for X. (5 points)

Show the data types of the X columns. (5 points)

Split the data into training and testing sets. (5 points)

Encode all X data to numeric types. (5 points)

Scale the X data. (5 points)

Encode all y data to numeric types. (5 points)

Model (40 points)
Find the number of columns in the X training data. (5 points)

Create an input layer. (5 points)

Create at least two shared hidden layers. (10 points)

Create an output branch for the department column. (10 points)

Create an output branch for the attrition column. (10 points)

Summary (20 points)
Answer the questions briefly. (10 points)

Show understanding of the concepts in your answers. (10 points)

Grading
This challenge will be evaluated against the requirements and assigned a grade according to the following table:

Grade	Points
A (+/-)	90+
B (+/-)	80–89
C (+/-)	70–79
D (+/-)	60–69
F (+/-)	< 60
Submission
To submit your Challenge assignment, click Submit, and then provide the URL of your GitHub repository for grading.

note
You are allowed to miss up to two Challenge assignments and still earn your certificate. If you complete all Challenge assignments, your lowest two grades will be dropped. If you wish to skip this assignment, click Next, and move on to the next module.

Comments are disabled for graded submissions in Bootcamp Spot. If you have questions about your feedback, please notify your instructional staff or your Student Success Manager. If you would like to resubmit your work for an additional review, you can use the Resubmit Assignment button to upload new links. You may resubmit up to three times for a total of four submissions.

important
It is your responsibility to include a note in the README section of your repo specifying code source and its location within your repo. This applies if you have worked with a peer on an assignment, used code that you did not author or create, source code from a forum such as Stack Overflow, or received code outside curriculum content from support staff, such as an Instructor, TA, Tutor, or Learning Assistant. This will provide visibility to grading staff of your circumstance in order to avoid flagging your work as plagiarized.

If you are struggling with a Challenge or any aspect of the curriculum, please remember that there are student support services available to you:

Office hours facilitated by your TA(s)

Tutoring GuidelinesLinks to an external site. (schedule a session in the "Tutor Sessions" section of Bootcampspot)

Ask the class Slack channel/get peer support

AskBCS Learning Assistants

