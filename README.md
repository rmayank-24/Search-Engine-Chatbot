# 🔍 Search Engine Chatbot

A powerful AI chatbot built using **LangChain** and **Groq's LLaMA3-8B model**, capable of searching the web via **DuckDuckGo**, **Wikipedia**, and **Arxiv** to provide live and contextual answers to your queries.

🔗 **Live App**: [https://search-engine-chatbot.streamlit.app](https://search-engine-chatbot.streamlit.app)

---

## 🚀 Features

* 🌐 **Real-time search** using DuckDuckGo
* 📚 **Wikipedia integration** for encyclopedic context
* 📄 **ArXiv support** for academic-level responses
* 💬 Conversational chatbot interface (Streamlit)
* 🤖 Uses **Groq API** for ultra-fast responses (LLaMA3-8B)

---

## 🛠️ Tech Stack

* **Frontend/UI**: Streamlit
* **LLM**: LLaMA3-8B via [Groq API](https://console.groq.com/)
* **Framework**: LangChain
* **Tools**:

  * DuckDuckGoSearchRun
  * WikipediaQueryRun
  * ArxivQueryRun
* **Languages**: Python
* **Env Management**: python-dotenv

---

## 🧑‍💻 How It Works

1. User enters a query via Streamlit chat input.
2. The chatbot uses LangChain's Zero-Shot ReAct agent with access to three tools:

   * DuckDuckGo (search)
   * Wikipedia
   * Arxiv
3. Response is generated and streamed using LLaMA3-8B from Groq.

---

## 📦 Installation

```bash
git clone https://github.com/rmayank-24/Search-Engine-Chatbot.git
cd Search-Engine-Chatbot
pip install -r requirements.txt
```

Add your Groq API Key in a `.env` file:

```env
GROQ_API_KEY=your_key_here
```

---

## 🧪 Run the App Locally

```bash
streamlit run app.py
```

---


## 🙌 Acknowledgements

* [LangChain](https://www.langchain.com/)
* [Groq](https://console.groq.com/)
* [Arxiv API](https://arxiv.org/help/api/index)
* [Wikipedia API](https://www.mediawiki.org/wiki/API:Main_page)
* [DuckDuckGo Search](https://pypi.org/project/duckduckgo-search/)

---

## 📜 License

This project is licensed under the MIT License.
