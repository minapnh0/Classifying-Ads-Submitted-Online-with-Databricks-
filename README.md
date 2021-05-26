# Classifying Ads Submitted Online with Databricks 
 
Consider the case of a website that caters to the needs of a specific farming community, and carries classified ads intended for that community. Anyone, including robots, can post an ad via a web interface, and the site owners have problems with ads that are fraudulent, spam, or simply not relevant to the community. They have provided a file with 4143 ads, each ad in a row, and each ad labeled as either -1 (not relevant) or 1 (relevant). The goal is to develop a predictive model that can classify ads automatically.

Open the file farm-ads.csv, and briefly review some of the relevant and non-relevant ads to get a flavor for their contents.
• Following the class example, please create the TF-IDF feature matrix. a. Examine the TF-IDF matrix. i. Is it sparse matrix or dense matrix? (Or answer How much percentage of the entries in the
matrix is zero?) ii. Find two non-zero entries and briefly interpret their meaning, in words. (you do not need to derive their calculation)

b. Using logistic regression, partition the data (60% training, 40% validation), and develop a model to classify the documents as ‘relevant’ or ‘non-relevant.’ Comment on your model’s accuracy.
