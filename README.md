# Stock_Tweet_Sentiment_Anlaysis

This Repo focuses on sentiment analysis of stock-related tweets, aiming to extract insights from social media data for better understanding market sentiment. The workflow begins with preprocessing steps, including the removal of punctuation and stopwords using the Gensim library, followed by visualization of word frequency using word clouds. Tokenization is then employed to convert text data into sequences of tokens for model input.

Model selection is conducted using TPOT, a powerful automated machine learning library. TPOT explores a range of machine learning algorithms, including Support Vector Machines (SVM), Naive Bayes, and Random Forest, to identify the most effective model for sentiment analysis.

The chosen architecture for sentiment analysis utilizes deep learning techniques implemented with TensorFlow's Keras API. The model comprises an embedding layer to represent words in a dense vector space, followed by an LSTM (Long Short-Term Memory) layer for sequence processing. Dropout regularization is applied to prevent overfitting, and a dense layer with ReLU activation is added for non-linearity. The model is trained with the Adam optimizer and binary crossentropy loss function.

Performance evaluation is conducted by comparing the deep learning model's accuracy with that of Random Forest, identified as the best-performing model by TPOT. The results demonstrate the effectiveness of the deep learning architecture in capturing nuanced sentiment patterns from stock-related tweets, showcasing its potential for enhancing market sentiment analysis.
