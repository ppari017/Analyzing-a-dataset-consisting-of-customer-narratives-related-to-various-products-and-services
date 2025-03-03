# Analyzing a dataset consisting of customer narratives related to various products and services for a company

The dataset contains three columns: "complaint_no", "product", and "narrative". The "complaint_no" column represents an identifier for each entry, while the "product" column specifies the type of product or service associated with each narrative. The "narrative" column contains the actual text data, which comprises descriptions, complaints, inquiries, or feedback from customers.
Our goal is to perform exploratory data analysis (EDA) on this dataset to gain insights into the types of issues customers are experiencing across different products or services. This analysis will help the company understand customer pain points better, prioritize areas for improvement, and enhance overall customer satisfaction. In addition to performing exploratory data analysis (EDA), build a model to categorize the customer narratives into different product/service categories based on their content. We employ natural language processing (NLP) techniques and a Bidirectional Long Short-Term Memory (Bi-LSTM) neural network architecture to evaluate and interpret the model, and compare with two traditional classifiers, (e.g., Naïve Bayes & Random Forest).

**Result:**

The Naïve Bayes classifier achieved an accuracy of 36.12%, while the Random Forest classifier achieved an accuracy of 81.86%. The Bi-LSTM model demonstrates better performance compared to the above two traditional classifiers with an accuracy of 88.54%.
