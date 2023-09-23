# Chat with PDF

## Clone the Repo:

Clone the repository.

```shell
git clone https://github.com/thestackdev/palm-chatbot.git
```

## Environment Setup

In order to set your environment up to run the code here, first install all requirements:

```shell
python -m venv env
source env/bin/activate
pip install -r requirements.txt
```

## OpenAI API Key

You will need the PaLM API key to run this, get your PaLM key from [here](https://developers.generativeai.google/)
In the `.env` set your API key.

```shell
GOOGLE_API_KEY=
```

## Run the WebApp:

```shell
streamlit run main.py
```
