# FinancialBERT

![Demo GIF](./assets/FinancialBERT_Streamlit_Demo_Speedup.gif)

### About
---
- Stock price prediction model built using BERT and regression model trained on textual financial news data.
- RAG system built on top of trained model for interactable application for predicting next month's stock price from real-world financial news headlines.
- Demonstrates an alternative approach to the current time-series models for financial predictions.
- Research paper published on [ResearchGate](https://www.researchgate.net/publication/376356600_FinancialBERT_Predicting_Stock_Price_with_BERT_and_Semantic_Analysis).
<a href="https://www.researchgate.net/publication/376356600_FinancialBERT_Predicting_Stock_Price_with_BERT_and_Semantic_Analysis">
    <img src="./assets/FinancialBERT_Research_Paper_Page1.png" width="400" alt="description of the image"/>
</a>

### Project Structure
---
- `finance_bert_monthly_data_engineering.ipynb` contains code to extract training data from financial news datasets from Kaggle and stock price history data from Polygon.io.
- `data.zip` contains all training data (no need to run the above notebook yourself) called `stock_data.zip` and `cleaned_training_data.jsonl`, as well as `tickers_and_names.csv` file needed for the RAG system.
- `financial_bert_monthly_prediction_training_from_embedding_v1.ipynb` contains source code to train the Model v1 from the research paper.
- `financial_bert_monthly_prediction_training_from_embedding_v2.ipynb` contains source code to train the Model v2 from the research paper (the model used for the RAG system).
- `financial_bert_monthly_prediction_training_from_probabilities_top_5_k.ipynb` contains source code to train the Model Top 5k from the research paper.
- `financial_bert_rag_system.ipynb` contains source code to run the Streamlit app for interactive stock price prediction app.
- Additionally, the trained regression model weights can be downloaded from my Google Drive: [https://drive.google.com/file/d/1g-HDbEMdaMrWHFKxjE7UmLu_Tf8kwhqB/view?usp=sharing](https://drive.google.com/file/d/1g-HDbEMdaMrWHFKxjE7UmLu_Tf8kwhqB/view?usp=sharing)
