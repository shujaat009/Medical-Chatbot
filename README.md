# End-to-end-Medical-Chatbot


# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/shujaat009/Medical-Chatbot.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.12 -y
```

```bash
conda activate medibot
```


### STEP 02- install the requirements

```bash
pip install langchain langchain_community langchain_huggingface faiss-cpu pypdf
pip install huggingface_hub
pip install streamlit
```


### Create a `.env` file in the root directory and add your hugging face credentials as follows:

```ini
HF_TOKEN = "xxxxxxxxxxxxxxxxxxxxxxxxxx"
```

```bash
# run the following command to create memory for llm
python create_memory_for_llm.py
```

```bash
# run the following command to connect memory with llm
python connect_memory_with_llm.py
```


```bash
# Finally run the following command
python medicalbot.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- Streamlit
- HuggingFace
