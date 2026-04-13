 Zomato Indian Restaurants — Exploratory Data Analysis
A solo, end-to-end EDA project on Zomato's Indian restaurant dataset — my first real-world data analysis project built from scratch using Python.

📌 Project Summary
This project explores Zomato's dataset of Indian restaurants spanning 99 cities and 3,700+ localities. The goal was to go beyond surface-level analysis and uncover meaningful patterns in cuisine preferences, customer behavior, pricing, and restaurant engagement across India.
The dataset was messy — cuisines were bundled into single cells, establishment types had formatting inconsistencies, zipcodes were largely missing, and beverage entries were mixed in with food cuisines. A significant portion of the project was dedicated to cleaning and standardizing the data before any analysis could begin.
Once cleaned, the analysis focused on five key questions: Which cuisines dominate city by city? Which restaurants are most popular vs. most highly rated — and do they ever match? Which establishment types drive the most customer engagement? How does pricing vary across cities? And how skewed is vote distribution across restaurants?

🔍 Key Insights

North Indian cuisine dominates almost every major city, showing strong nationwide demand over regional alternatives like South Indian or Chinese.
The most popular restaurant is rarely the highest rated. City-level comparison reveals a consistent gap between order count and customer satisfaction — popularity ≠ quality.
Microbreweries punch above their weight. Despite being far fewer in number than Casual Dining restaurants, Microbreweries record the highest average votes and ratings — pointing to a quality-driven, highly engaged customer base.
Pricing follows tourism and metro patterns. Cities like Goa show the highest average price range, while smaller cities skew budget-friendly — strongly influenced by local demand and cost of living.
Votes are heavily skewed. Only 48 restaurants out of the entire dataset have more than 10,000 votes — a small elite capturing the majority of customer attention.
Palmshore (Chennai) is the single most-ordered restaurant in the dataset, followed by Sweet Magic, which dominates across Vijayawada and Guntur.


🛠️ Tech Stack
ToolPurposePythonCore analysisPandasData cleaning & manipulationSeabornStatistical visualizationsMatplotlibCustom charts & plots

📂 Project Structure
zomato-eda/
│
├── Zomato_EDA.ipynb       # Main analysis notebook
├── README.md              # Project documentation
└── Indian-Resturants.csv  # Dataset (source: Zomato / Kaggle)

💡 What I Learned

How to handle real-world messy data — multi-valued columns, missing zips, inconsistent formatting
The importance of data standardization decisions (e.g. whether Awadhi → North Indian is the right call)
How to frame analysis around business questions, not just code
That the most interesting insights often live in comparisons — not single metrics


