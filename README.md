# Knowledge-Graph-based-QnA

We try to combine two significant approaches to a Question Answering System. These two distinct approaches have proved to provide answers to the questions when we input a paragraph. The first approach is a Bidirectional Attention Flow (BiDAF) model for Machine Comprehension. It uses the attention flow mechanism and bi-directional Long Short Term Memory (LSTM) in its architecture. It has been trained on Stanford Question Answering Dataset (SQuAD). The other approach is Entity pairs Extraction and Knowledge Graph Construction. This method extracts entities from each sentence of the paragraph and constructs a knowledge graph which are used to answer the questions inputted by the user.

Simply run in terminal,

'python3 init.py -i <Text File> -q <Question with " ">'

For example:

'python3 init.py -i new.txt -q "Who ate chocolate?"'
