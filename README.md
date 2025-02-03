# local-chatgpt

## Description
This is pretty much a hello-world example that allows you to spin up a fully local chat-gpt clone with minimal effort.

## Requirement
- Python 3.11+
- [Ollama](https://ollama.com/)
- [Supported hardware](https://github.com/ollama/ollama/blob/main/docs/gpu.md)
  
## Installation
1. Download and install Ollama
2. Clone this repo and switch into it
3. `python3 -m venv venv`
4. `. ./venv/bin/activate`
5. `pip install -r requirements.txt`
6. `chainlit run local-chatgpt.py -w`

If everything worked well the last command should have told you an URL to connect to or possibly even opened you a browser to it.

Have fun.