# CloneGPT

This repository contains code that demonstrates a basic implementation of a ChatGPT clone using the Gradio library. The ChatGPT clone allows users to have interactive conversations with an AI assistant powered by the OpenAI GPT-3.5 model.

## Usage

1. Clone the repository:

   ```shell
   git clone https://github.com/rishii100/CloneGPT.git
### Install the required dependencies:

     pip install -r requirements.txt

### Replace the placeholder API key:

2.Open the **main.py** file.

3.Find the line ` openai.api_key = "Enter your API key" `.

4.Replace **"Enter your API key"** with your actual **OpenAI API key**.

### Run the application:
  ``` 
     python main.py 
   ``` 


5.Open your web browser and navigate to ` http://localhost:7860 ` to access the ChatGPT clone interface.

6.Enter your messages in the text input box and click the "SEND" button to send them to the AI assistant. The AI 
  assistant will generate responses based on the conversation history.
## Dependencies:

1)**Python 3.6** or above

2)**openai** library

3)**gradio** library

## Disclaimer:
The AI assistant is powered by the OpenAI GPT-3.5 model and the responses are generated based on the training data it has been exposed to. Please note that the AI assistant's responses may not always be accurate or appropriate. Use the code and the AI assistant at your own risk.
