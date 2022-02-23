# fastText on Wikipedia
In this repository we publish several fastText embeddings trained on Wikipedia data.
Used software and data:
- fastText: [v0.9.2](https://github.com/facebookresearch/fastText/releases/tag/v0.9.2)
- Wikipedia text corpus from: [GermanT5/wikipedia2corpus](https://github.com/GermanT5/wikipedia2corpus)

## de skipgram 64d
- `fasttext skipgram -input ../data/dewiki-20220201-clean.txt -output de-wikipedia-skipgram-64 -dim 64`
