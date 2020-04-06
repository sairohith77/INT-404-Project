# HealthCare Chatbot System
This healthcare chatbot system will help hospitals to provide healthcare support online 24 x 7. By asking the questions in series it helps patients by guiding what exactly he/she is looking for.
## What is a Chatbot?
A chatbot is an intelligent piece of software that is capable of communicating and performing actions similar to a human. Chatbots are used a lot in customer interaction, marketing on social network sites and instantly messaging the client. There are two basic types of chatbot models based on how they are built; Retrieval based and Generative based models.
## About the AI Project-Chatbot
In this AI project with source code, we are going to build a chatbot using deep learning techniques. The chatbot will be trained on the dataset which contains categories (intents), pattern and responses. We use a special recurrent neural network (LSTM) to classify which category the user’s message belongs to and then we will give a random response from the list of responses.
Let’s create a retrieval based chatbot using NLTK, Keras, Python, etc.
The dataset we will be using is ‘intents.json’. This is a JSON file that contains the patterns we need to find and the responses we want to return to the user.
Intents.json – The data file which has predefined patterns and responses.
train_chatbot.py – In this Python file, we wrote a script to build the model and train our chatbot.
Words.pkl – This is a pickle file in which we store the words Python object that contains a list of our vocabulary.
Classes.pkl – The classes pickle file contains the list of categories.
Chatbot_model.h5 – This is the trained model that contains information about the model and has weights of the neurons.
Chatgui.py – This is the Python script in which we implemented GUI for our chatbot. Users can easily interact with the bot.
Here are the 5 steps to create a chatbot in Python from scratch:
1. Import and load the data file
2. Preprocess data
3. Create training and testing data
4. Build the model
5. Predict the response
To run the chatbot, we have two main files; train_chatbot.py and chatapp.py.
First, we train the model using the command in the terminal:python train_chatbot.py
If we don’t see any error during training, we have successfully created the model. Then to run the app, we run the second file.
Using the command in terminal:python chatgui.py
The program will open up a GUI window within a few seconds. With the GUI you can easily chat with the bot.
