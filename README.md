# CMPS 6730 Project-codenames
The goal of this project was to automate the role fo the spymaster in the popular board game - Codenames. Methods and tools used in this project are using the gensim pretrained Word2Vec Model on the GoogleNews-vectors-negative300 dataset. Other Tools used in this project are the NLTK corups on WordNet as well as scikit-learns TSNE to help with the plotting. 

### Contents

- [nlp](nlp): Python project code in a final notebook called NLP_project.ipynb
- [notebooks](notebooks): Contains a notebook where all the experiementation were conducted
- [report](report): LaTeX report with results and discussion can be found here in pdf format.


### Experimentation
INitially we experimented with using pre trained transformers from the hugging face library, as well as tried using the knowledge graph ConceptNet. Eventually we settled to use pretrained word2vec models from the gensim library. And were able to generate better clues with the help from synsets from the NLTK wordnet library. 

### Results
As we can see from our plots and the clues outputted. Our clues arent as good as they should be. We think this is either because of the dataset we used or because of the board randomization. With some boared randomization s we are able to achieve good results but with others we recieve clues that are not too helpful. 



