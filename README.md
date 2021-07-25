# Learning NLP with SpaCy 2.6
The following notebooks provide a demonstration the features that you can expect from a Natural Processing Engine, starting simple task such as Tokenization to advanced analysis such as Named Entity recognition. 
Each notebook focuses on one feature that has been shown with SpaCy 2.6 with the English model. Please refer to [SpaCy documentation](https://v2.spacy.io/usage) for more details.


##Let's start 
You can fork and/or clone this repository and get all the notebooks available.

```bash
git clone https://github.com/nluninja/nlp_crash_course
```

## Available Notebooks

| Name | Description | classes | format | language |
| ---- | ----------- | ------- | ------ | -------- |
| [`NLP Basics`](./20_newsgroup/) | file set arranged into 20 topic folders | see corpus page | files | en  |
| [`Tokenization`](./ag_news/) | News Topic Classification dataset - Antonio Gulli -  UniPi | World, Sports, Business, Sci/Tech | csv | en  |
| [`Stemming`](./conll2003/) | named entity recognition dataset | People, Location, Organization, Misc | conll/iob2 | en  |
| [`Lemmatization`](./emotion_classification_dataset/) | emotion classification dataset which contains tweets labeled into 6 categories | joy, sadness, anger, fear, love, surprise | csv | en |
| [`Stop Words`](./GUM/) | CoNLL tagged corpus for entity extraction| 23 classes (person, substance, quantity, time, place, organization) | conll/iob2 | en  |
| [`Part-of-Speech`](./re3d/) | CoNLL tagged corpus for entity extraction| 21 classes (person, temporal, weapon, MilitaryPlatform, quantity, organization) | conll/iob2 | en  |
| [`Visualizing PoS`](./sentiment140_dataset/) | dataset which contains tweets labeled according to their polarity |negative, neutral, positive | csv | en |
| [`Named Entities`](./toxic_comments/) | Wikipedia comments labeled into 6 categories with score | toxic, severe_toxic, obscene, threat, insult, identity_hate| csv | en  |
| [`Visualizing-NER`](./yelp_reviews/) | reviews dataset from Yelp! for classification/sentiment analysis tasks| 1 to 5 rates | csv | en  |

