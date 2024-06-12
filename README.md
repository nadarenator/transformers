# transformers
Finetuning various transformer architectures on a variety of standard NLP datasets using hugging face, pytorch, and other associated frameworks. 
## Sentiment Analysis
### [finetuning_sentiment.ipynb](./finetuning_sentiment.ipynb):
- Dataset: [glue sst2](https://huggingface.co/datasets/nyu-mll/glue#sst2)
- Model: [distillbert (uncased)](https://huggingface.co/docs/transformers/v4.41.3/en/model_doc/distilbert#distilbert)
### [finetuning_sentiment_custom.ipynb](./finetuning_sentiment_custom.ipynb):
- Dataset: [twitter airline sentiment](https://www.kaggle.com/crowdflower/twitter-airline-sentiment)
- Model: [distillbert (cased)](https://huggingface.co/docs/transformers/v4.41.3/en/model_doc/distilbert#distilbert)
## Textual Entailment
### [finetuning_entailment.ipynb](./finetuning_entailment.ipynb):
- Dataset: [glue rte](https://huggingface.co/datasets/nyu-mll/glue#rte)
- Model: [bert (cased)](https://huggingface.co/google-bert/bert-base-cased)
## Named Entity Recognition
### [finetuning_ner.ipynb](./finetuning_ner.ipynb):
- Dataset: [conll2003](https://huggingface.co/datasets/eriktks/conll2003)
- Model: [bert (cased)](https://huggingface.co/google-bert/bert-base-cased)
## Parts-of-Speech Tagging
### [finetuning_pos_custom.ipynb](./finetuning_pos_custom.ipynb):
- Dataset: [brown corpus](https://www.nltk.org/book/ch02.html)
- Model: [bert (cased)](https://huggingface.co/google-bert/bert-base-cased)
## Neural Machine Translation
### [finetuning_translation.ipynb](./finetuning_translation.ipynb):
- Dataset: [Helsinki-NLP kde4](https://huggingface.co/datasets/Helsinki-NLP/kde4)
- Model: [Helsinki-NLP opus-mt-en-hi](https://huggingface.co/Helsinki-NLP/opus-mt-en-hi)
***
P.S. This was done on a singular RTX2060Ti GPU, hence the selection of relatively lightweight models and datasets.