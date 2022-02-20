This project was undertaken as part of the Post Graduate Diploma Program of IIIT Hyderabad (organized by TalenSprint). The objective was to classify a collection of BBC news stories from five topical areas, conisiting of 2225 documents from the BBC news website of the year 2004 and 2005. These articles were labled into five categories:  business, entertainment, politics, sport, tech.

This project was jointly done by Somasundaram Chidambaram and Vinod Thomas

# BBC_BoW_final.ipynb

Simple Bag of Words method was used to vectorize the news articles. Thereafter various machine learning algorithms were applied on the vectors. The test accuracies obtained are as follows: 
KNN 0.69
SVC 0.96
Random Forest 0.86
Gradient Descent 0.96
Logistic Regression 0.97

# BBC_tfidf_final.ipynb
Tfidf was used to vectorize the news articles. On applying various ML algorithms on the dataset, the following accuracy scores were obtained. 
KNN 0.96
SVC 0.98
Random Forest 0.81
Gradient Descent 0.98
Logistic Regression 0.98

# BBC_cnn_final.ipynb
One dimensional convolutional neural network was applied on the dataset. We used three kernels of 3, 4 and 5-grams. The resulting accuracy was 0.97.

# BBC_LSTM_Final.ipynb
LSTM was applied on the dataset to arrive at an accuracy of 0.90

# BBC_BERT_final.ipynb
On applying BertForSequenceClassification, at 3 epochs, an accuracy of 0.95 was achieved.

# BBC_cnn_Deployment.ipynb
This is the version of BBC_cnn_final.ipynb that was deployed.
