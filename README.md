# Complete code will be added by 23rd May.
# Jigsaw-Multilingual-Toxic-Comment-Classification
### Challenge Description:


It only takes one toxic comment to sour an online discussion. The Conversation AI team, a research initiative founded by Jigsaw and Google, builds technology to protect voices in conversation. A main area of focus is machine learning models that can identify toxicity in online conversations, where toxicity is defined as anything rude, disrespectful or otherwise likely to make someone leave a discussion. If these toxic contributions can be identified, we could have a safer, more collaborative internet.

In the previous 2018 Toxic Comment Classification Challenge, Kagglers built multi-headed models to recognize toxicity and several subtypes of toxicity. In 2019, in the Unintended Bias in Toxicity Classification Challenge, you worked to build toxicity models that operate fairly across a diverse range of conversations. This year, we're taking advantage of Kaggle's new TPU support and challenging you to build multilingual models with English-only training data.

Jigsaw's API, Perspective, serves toxicity models and others in a growing set of languages (see our documentation for the full list). Over the past year, the field has seen impressive multilingual capabilities from the latest model innovations, including few- and zero-shot learning. We're excited to learn whether these results "translate" (pun intended!) to toxicity classification. Your training data will be the English data provided for our previous two competitions and your test data will be Wikipedia talk page comments in several different languages.

As our computing resources and modeling capabilities grow, so does our potential to support healthy conversations across the globe. Develop strategies to build effective multilingual models and you'll help Conversation AI and the entire industry realize that potential.

Disclaimer: The dataset for this competition contains text that may be considered profane, vulgar, or offensive.

Repository:

1. Understanding and Cleaning Data.ipynb => Loading, Visualization using wordcloud, data cleaning.

Rest of the files are organised in separate folders.


Complete code will be added by 23rd May.

Few Observations/challenges/learnings
1. LSTM were taking longer to train then RNN and GRU.
2. GRU as expected was fastest out of tried architecture.
3. Data Cleaning helped to some extent in reducing model training time.
4. Observed how changing batch size can affect loss and training time of the model.
5. Trained models with over 4 lakh trainable parameters.
