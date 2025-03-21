# AI-chatbot-calculator
An AI-powered chatbot calculator that understands natural language inputs, extracts mathematical expressions, and computes results. Built using Python, this project combines Natural Language Processing (NLP) with mathematical computation to provide a seamless user experience

Python 3.8+
Libraries:
transformers (for NLP)
sympy (for mathematical computation)
torch (backend for transformers)

Input Processing: The chatbot uses a pre-trained NLP model (distilbert-base-uncased) to classify user input and identify math-related queries.
Expression Extraction: A regex pattern extracts mathematical expressions from the user's input.
Computation: The extracted expression is evaluated using the sympy library, and the result is returned to the user.
Interactive Loop: The chatbot runs in a loop, allowing users to perform multiple calculations until they choose to exit.
