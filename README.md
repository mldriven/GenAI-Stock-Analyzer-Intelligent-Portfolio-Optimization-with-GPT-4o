## GenAI-Stock-Analyzer-Intelligent-Portfolio-Optimization-with-GPT-4o

This project combines the power of GPT-4o, LangChain, and yFinance with modern portfolio theory to create an intelligent stock analysis and optimization tool. It leverages PyPortfolioOpt, pandas, and LLM prompt engineering to drive smart investment decisions from historical stock data.

Tools & Libraries Used:
- GPT-4o via LangChain for code generation, financial interpretation, and intelligent prompting
- yFinance for historical stock price retrieval
- PyPortfolioOpt for portfolio construction and optimization
- pandas, matplotlib for data manipulation and visualization

Top KPIs Calculated:
The system computes and visualizes 10 key performance indicators per asset using LLM-generated code, including:
1. Annual Return
2. Volatility
3. Sharpe Ratio
4. Cumulative Returns
5. Drawdown
6. Beta
7. Alpha
8. Moving Averages
9. RSI
10. Bollinger Bands

The LLM-generated code fetches stock data using yFinance, computes all KPIs per ticker, and then structures the output into a clean dictionary of tickers and their associated KPI metrics. This dictionary is used to represent each asset’s quantitative profile in a modular format.

Prompt engineering was applied iteratively to GPT-4o to:
- Generate dynamic code for computing financial KPIs
- Visualize time-series insights for each KPI
- Create optimal portfolios using Black-Litterman and Efficient Frontier models
- Interpret results and recommend asset weightings with natural language summaries

To conclude this project showcases how GenAI can bridge the gap between finance and AI by generating and interpreting market insights autonomously. It illustrates the potential of LLMs in financial analytics, making portfolio management more explainable, scalable, and interactive.
