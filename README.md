**Chatbot Project**

Introduction
This project is an example of building a simple chatbot using Python and Keras. The chatbot is trained on a dataset containing intents and responses, allowing it to understand and respond to user messages.

Features
- Responds to user messages with appropriate intents.
- Trained on a dataset containing a variety of intents.
- Uses a neural network model for classification.
- Utilizes natural language processing techniques.

Installation
1. Clone the repository:
    git clone https://github.com/yashc1712/chatbot-project.git

2. Navigate to the project directory:
    cd chatbot-project

3. Install the required dependencies:
    pip install -r requirements.txt

## Usage
1. Train the chatbot model:
    python training.py

2. Run the chatbot:
    python chatbot.py

3. Enter messages in the terminal to interact with the chatbot.

## Project Structure
- `chatbot.py`: Main script to run the chatbot.
- `training.py`: Script to train the chatbot model.
- `chatbot/intents.json`: JSON file containing intents and responses.
- `words.pkl`: Pickle file containing processed words.
- `classes.pkl`: Pickle file containing classes.
- `chatbot_model.h5`: Trained chatbot model.
