## 🚀 Project Overview

This project explores advanced usage of **Large Language Models (LLMs)** through the **LangChain** framework, integrating multiple providers and adding efficient token handling and structured prompting.

---

## 🧠 Features

- 🔗 **Multi-LLM Integration**  
  Seamlessly interacts with different LLM providers:
  - OpenAI
  - Llama
  - Groq  

- ⚙️ **LangChain Orchestration**  
  Uses LangChain to manage prompts, chains, and model interactions in a modular and scalable way.

- ✂️ **Tokenization with Tiktoken**  
  Efficient token counting and management to optimize cost and performance.

- 🧩 **Structured Prompting**  
  Carefully designed prompts to enforce consistent and machine-readable outputs.

- 📊 **Sentiment Analysis Pipeline**  
  Final implementation performs sentiment analysis on PC components:
  - ⌨️ Keyboard  
  - 🖱️ Mouse  
  - 🟫 Mouse Pad  

  Output is returned in structured JSON format for easy downstream processing.

---

## 🏗️ Tech Stack

- 🐍 Python  
- 🔗 LangChain  
- 🤖 OpenAI / Llama / Groq APIs  
- ✂️ Tiktoken  

---

## 🎯 Goal

The goal of this project is to demonstrate:
- How to orchestrate multiple LLMs efficiently  
- How to control outputs using structured prompts  
- How to optimize token usage in real-world applications  

---

## 📦 Example Output

```json
{
  "keyboard": "positive",
  "mouse": "negative",
  "pad": "neutral"
}