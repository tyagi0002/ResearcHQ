# 🧠 ResearcHQ – AI Research Assistant using LangChain & Gemini

ResearcHQ is an intelligent research assistant built using LangChain, Google's Gemini API, and external tools like Wikipedia and DuckDuckGo. It answers your research queries, fetches relevant information, and saves the structured output.

---

## 🚀 Features

- 🔍 Web and Wikipedia Search
- 📄 Structured Summary Generation
- 💾 Auto-saving Research Output to File
- 🧠 Gemini-powered LLM Integration
- 🛠 Tool-based Agent with LangChain

---

## 📁 Project Structure

```bash
├── main.py             # Main entry point, initializes and runs the agent
├── tools.py            # Defines custom tools like search, wiki, save
├── requirements.txt    # Project dependencies

## 🛠️ Installation

Make sure you have Python 3.8+ installed.

Install core dependencies
Install all required packages using the requirements.txt file::

```bash
pip install -r requirements.txt

pip install --upgrade langchain langchain-community

pip install -U langchain-google-genai

pip install tools
