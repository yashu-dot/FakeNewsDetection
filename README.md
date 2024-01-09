# Fake News Detection using Deep Learning and NLP

**Abstract**

In today's internet-driven world, the rapid dissemination of news through social media platforms has led to the swift spread of fake news. The consequences of fake news range from biased opinions to influencing election outcomes. This project addresses the challenge of detecting fake news by employing a classification model based on deep learning and NLP techniques. The model is trained on an ISOT fake news dataset and tested on real-time data from Indian news sources.

**Key Features**

Custom neural network architecture
Word2Vec for text transformation
LSTM layers for memory retention
Training and validation on ISOT fake news dataset
Testing on Indian news websites: Times of India and Politifact
Data cleaning, analysis, and preprocessing
Results presented in terms of accuracy for different datasets and combinations of title and description
Future work and potential use cases discussed

**Dataset**

The model is trained on the ISOT fake news dataset, which includes two CSV files: Fake.csv and Real.csv. The dataset contains news titles, text, topics, publication dates, and labels indicating whether the news is fake or real.

**Results**

Training Data Accuracy: 99%
Times of India Testing Accuracy: 75.01% (Title + Description), 68.18% (Only Description), 71.3% (Only Title)
Politifact Testing Accuracy: 66.67% (Title + Description), 61.66% (Only Description), 63.34% (Only Title)

**Future Works**

Integration with social media platforms
UI for user-driven authenticity checks
Extension to other languages and nations
Handling unformatted data in an unsupervised manner

**Conclusion**

This project presents an effective deep learning approach for classifying real and fake news using traditional NLP methods. The model achieves high accuracy on training data and reasonable accuracy on real-time data from Indian news websites.

**References**

[1] Marín, Ignacio & Arroyo, David. (2021). Fake News Detection: Do Complex Problems Need Complex Solutions?

[2] Hamid, Abdullah et al. (2020). Fake News Detection in Social Media using Graph Neural Networks and NLP Techniques: A COVID-19 Use-case.

[3] T. Traylor, J. Straub, Gurmeet and N. Snell, "Classifying Fake News Articles Using Natural Language Processing to Identify In-Article Attribution as a Supervised Learning Estimator," 2019 IEEE 13th International Conference on Semantic Computing (ICSC).

[4] Oshikawa, R., Qian, J., & Wang, W.Y. (2020). A Survey on Natural Language Processing for Fake News Detection.

[5] V. V. Hirlekar and A. Kumar, "Natural Language Processing based Online Fake News Detection Challenges – A Detailed Review," 2020 5th International Conference on Communication and Electronics Systems (ICCES).

[6] A. Jain, A. Shakya, H. Khatter and A. K. Gupta, "A smart System for Fake News Detection Using Machine Learning," 2019 International Conference on Issues and Challenges in Intelligent Computing Techniques (ICICT).

[7] R. K. Kaliyar, "Fake News Detection Using A Deep Neural Network," 2018 4th International Conference on Computing Communication and Automation (ICCCA).

[8] Hossain, Md & Rahman, Md & Islam, Md Saiful & Kar, Sudipta. (2020). BanFakeNews: A Dataset for Detecting Fake News in Bangla.

[9] Ahmed, Hadeer et al. (2017). Detecting opinion spams and fake news using text classification.

[10] Ahmed H, Traore I, Saad S. (2017) “Detection of Online Fake News Using N-Gram Analysis and Machine Learning Techniques.

[11] S. Hochreiter and J. Schmidhuber, "Long Short-Term Memory," in Neural Computation.

[12] Shu, Kai et al. (2017). Fake News Detection on Social Media: A Data Mining Perspective.

[13] Detecting Fake News in Social Media Networks. (2018, January 1). ScienceDirect.

[14] Zhang, J., Dong, B., & Yu, P. S. (2020). FakeDetector: Effective Fake News Detection with Deep Diffusive Neural Network. 2020 IEEE 36th International Conference on Data Engineering (ICDE).
