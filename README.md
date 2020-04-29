# NLP with spaCy 
This repo contains example notebooks for NLP workflows using the spaCy library.

## Installation
Install the required dependencies (for Python 3.6+) using a virtual environment:

```
python3 -m venv .env
source .env/bin/activate
pip3 install -r requirements.txt
```

For further development, simply activate the existing environment:
```
source .env/bin/activate
```

## Notebooks

1. Improving the performance of a spaCy workflow [[spacy_multiprocess.ipynb](https://github.com/prrao87/spacy-nlp/blob/master/spacy_multiprocess.ipynb)]: Speed up a spaCy pipeline using a combination of multiprocessing and custom language pipes.
