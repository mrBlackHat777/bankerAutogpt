# Leveraging Your Own Documents in a Langchain Pipeline
This project demonstrates the utilization of a ChromaDB vector store in a Langchain pipeline to create a GPT Personal Quant. By encoding PDF-based documents into vectors, their semantic and contextual information can be effectively captured. The integration of these vectors with a pre-trained Language Model enables rapid processing and analysis of large document volumes without the need for time-consuming fine-tuning. The GPT Personal Quant offers valuable insights and assistance in tasks like investment research, risk assessment, and portfolio management, making it a practical tool for the finance industry.



# Startup 🚀
1. Create a virtual environment `python -m venv langchainenv`
2. Activate it: 
   - Windows:`.\langchainenv\Scripts\activate`
   - Mac: `source langchain/bin/activate`
3. Clone this repo `git clone https://github.com/nicknochnack/LangchainDocuments`
4. Go into the directory `cd LangchainDocuments`
5. Install the required dependencies `pip install -r requirements.txt`
   - Linux:`Remove pywin32 from requirements.txt`
6. Add your OpenAI APIKey to line 22 of `app.py`
7. Start the app `streamlit run app.py`  


# Other References 🔗
<p>The main LG Agent used:<a href="https://python.langchain.com/en/latest/modules/agents/toolkits/examples/vectorstore.html">Langchain VectorStore Agents
</a></p>

<p>Vector databases :<a href="https://www.youtube.com/watch?v=klTvEwg3oJ4">Vector databases are so hot right now. WTF are they?
</a></p>


