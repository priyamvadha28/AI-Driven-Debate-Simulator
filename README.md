# AI-Driven-Debate-Simulator
The AI-Driven Debate Simulator is a Python-based project designed to simulate a debate between two classes using OpenAI's API. It generates arguments for each side of a debate, evaluates the conversation, and determines a winner based on the conversation history. The simulator uses OpenAI’s API to create debate arguments and summarize the debate, allowing users to observe how an AI can handle complex debate scenarios.

Functionality:
- Argument Generation: The simulator generates arguments for each side of the debate based on a predefined topic. It ensures that each argument is unique and relevant to the ongoing discussion.
- Debate Simulation: The debate alternates between the two classes, with each side providing arguments in turn. The conversation history is updated with each new argument.
- Winner Determination: After a set number of turns, the simulator summarizes the debate and determines the winner based on the overall conversation.

Setup:

1. Prerequisites:
Python 3.8 or higher
OpenAI API key

2. Installation:

Create a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Install the required packages: 
pip install -r requirements.txt

3. Configuration:
Obtain an API key from OpenAI and set it in the code where indicated.

Usage:

1.Edit the Code:
- Update the openai_api_key with your OpenAI API credentials.
- Modify the debate_topic and classes as needed for different debate scenarios.

2. Run the Script:
- Execute the script using Python:
pyhon debate_simulator.py

- The script will output the arguments from each side of the debate and the final winner.

Author:
This project is developed and maintained by Priyamvadha Pradeep.
