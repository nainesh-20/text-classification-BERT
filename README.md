

# Project: Automated Web Scraping and Text Classification Using BERT

1. Developed an automated web scraping tool using Python’s newspaper library to collect articles related to ‘games’ and ‘cars’ from various websites, creating a large and diverse dataset.
2. Performed data preprocessing including language detection to filter out non-English articles, and data reduction by randomly selecting two sentences from each article.
3. Split the data into training and testing sets with a train-test ratio of 0.2, ensuring a robust evaluation of the model’s performance.
4. Utilized the AutoTokenizer from the “bert-base-cased” model to tokenize the text data, converting it into a format suitable for the BERT model.
5. Trained a BERT model for sequence classification (TFAutoModelForSequenceClassification) on the tokenized training data, fine-tuning the model to classify text related to games and cars.
6. Evaluated the model’s performance on the test data, achieving an accuracy of 81.3%, demonstrating the model’s effectiveness in classifying text based on the topic.

This project showcased my skills in web scraping, data preprocessing, natural language processing, and machine learning model training and evaluation
