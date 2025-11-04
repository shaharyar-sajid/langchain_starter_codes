# LangChain Starter Notebooks

This repository is designed to **help you get started with the latest version of LangChain**.  
Many tutorials and courses available online still use **deprecated methods** that no longer work with the new `langchain` and `langchain_openai` packages.  

These notebooks bridge that gap by allowing you to **compare the old way vs the new way** side by side.

---

## 🧠 What You’ll Find

- 📘 **Beginner-friendly Jupyter notebooks (`.ipynb`)** to get started with LangChain.
- 🆕 **Examples using the latest LangChain APIs** (`RunnableSequence`, `RunnableMap`, etc.).
- 🧩 **Deprecated examples included for comparison**.

Each notebook shows both:
```python
# ✅ New way
result = llm.invoke("Tell me a joke about programming.")

# ❌ Older way (Deprecated)
result = llm("Tell me a joke about programming.")
```

# 🧩 Getting Started
## Clone the Repository
```bash
git clone https://github.com/shaharyar-sajid/langchain_starter_codes.git
cd langchain_starter_codes
```
## Create and Activate a Virtual Environment
It’s recommended to use a clean environment for LangChain projects:
```bash
# Using venv
python -m venv venv
source venv/bin/activate      # On macOS/Linux
venv\Scripts\activate         # On Windows
```
## Install Dependencies
A requirements.txt file has been provided. Install everything with:
```bash
pip install -r requirements.txt
```
## API Key Setup
LangChain automatically picks up your OpenAI key from the environment.
1. Create a .env file in the root of the project
2. Add your OpenAI API key inside:
```bash
OPENAI_API_KEY=sk-your-openai-key-here
```
LangChain will automatically load this key using dotenv.
