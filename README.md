# Basic-NLP-PreProcessing-with-Python

Basic Learning of Natural Language Processing : 
These Step before processing and dealing with any text-formatted Data
1. Tokenization : Process of separating a piece of text into smaller units called tokens
2. Stemming : Process of reducing inflected (or sometimes derived) words to their word stem, base or root form—generally a written word form
3. Lemmatization : In contrast to stemming, lemmatization looks beyond word reduction, and considers a language's full vocabulary to apply a morphological analysis to words.
4. Removing Stop words : What is stop words? is a list of collection word which does not add much meaning to a sentence. These word can safely be ignored without sacrificing the meaning of the sentence.

# Lemmas vs Stemming?

Stemming just removes or stems the last few characters of a word, often leading to incorrect meanings and spelling. Lemmatization considers the context and converts the word to its meaningful base form, which is called Lemma. Sometimes, the same word can have multiple different Lemmas.

1. lemmatize the word 'Caring', it would return 'Care'. If you stem, it would return 'Car' and this is erroneous.
2. lemmatize the word 'Stripes' in verb context, it would return 'Strip'. If you lemmatize it in noun context, it would return 'Stripe'. If you just stem it, it would just return 'Strip'
3. Lemmatization is computationally expensive. 
