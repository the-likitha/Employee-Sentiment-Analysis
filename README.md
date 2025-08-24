# Employee-Sentiment-Analysis
Sentiment Labeling

Use a pre-trained transformer model (e.g., HuggingFace transformers like distilbert-base-uncased-finetuned-sst-2-english) or a suitable sentiment analysis tool to classify each employee message in test.csv as Positive, Negative, or Neutral.

Output: Add a new column for sentiment labels to the dataset.

Exploratory Data Analysis (EDA)

Examine data overview: record count, columns, missing data.

Analyze the frequency distribution of sentiment labels.

Explore temporal trends by aggregating sentiment over dates/months.

Identify patterns or anomalies in message volume, sentiment by employee, or time.

Employee Score Calculation

Assign scores per message (+1 for Positive, 0 for Neutral, -1 for Negative).

Aggregate monthly sentiment scores for each employee by grouping by employee and month.

Employee Ranking

Based on monthly sentiment scores, create a ranked list of:

Top three positive employees (highest scores) each month.

Top three negative employees (lowest scores) each month.

Sort primarily by score, secondarily by employee name alphabetically.

Flight Risk Identification

Identify employees who sent 4 or more negative messages in any rolling 30-day window.

Extract and list these flight risk employees.

Predictive Modeling

Select features related to message characteristics, e.g., message frequency in a month, average message length.

Build a linear regression model to predict monthly sentiment score per employee.

Evaluate model performance and interpret coefficients.

Deliverables

A Jupyter notebook with code and commentary for all steps.

Visualizations (charts for EDA, rankings, flight risk flags, and model evaluation).

A final report summarizing methodology, insights, and model results.

A README.md summarizing key findings.
