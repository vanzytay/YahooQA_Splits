# YahooQA splits

Dataset splits for Yahoo Answers used in SIGIR 2017, AAAI 2018 and WSDM 2018
papers. Check the papers below for model comparisons on this dataset.

Original data comes from https://webscope.sandbox.yahoo.com/catalog.php?datatype=l

## Usage of dataset splits

You will find a `.pkl` file containing a dictionary object. The data
is split into train, test and dev, which are by itself, dictionaries
of the format train_QA[question] = [[ans1,0],[ans2,1],[ans3],0] etc..

Please contact me at ytay017@e.ntu.edu.sg if there are any issues. If I am
not supposed to be publicly releasing my dataset splits, please let me know
as well.

## Reference

If you use our dataset splits, please cite our paper:

```
@inproceedings{DBLP:conf/sigir/TayPLH17,
  author    = {Yi Tay and
               Minh C. Phan and
               Anh Tuan Luu and
               Siu Cheung Hui},
  title     = {Learning to Rank Question Answer Pairs with Holographic Dual {LSTM}
               Architecture},
  booktitle = {Proceedings of the 40th International {ACM} {SIGIR} Conference on
               Research and Development in Information Retrieval, Shinjuku, Tokyo,
               Japan, August 7-11, 2017},
  pages     = {695--704},
  year      = {2017},
  crossref  = {DBLP:conf/sigir/2017},
  url       = {http://doi.acm.org/10.1145/3077136.3080790},
  doi       = {10.1145/3077136.3080790},
  timestamp = {Sun, 06 Aug 2017 18:21:32 +0200},
  biburl    = {http://dblp.org/rec/bib/conf/sigir/TayPLH17},
  bibsource = {dblp computer science bibliography, http://dblp.org}
}
@article{DBLP:journals/corr/abs-1711-07656,
  author    = {Yi Tay and
               Luu Anh Tuan and
               Siu Cheung Hui},
  title     = {Cross Temporal Recurrent Networks for Ranking Question Answer Pairs},
  journal   = {CoRR},
  volume    = {abs/1711.07656},
  year      = {2017},
  url       = {http://arxiv.org/abs/1711.07656},
  archivePrefix = {arXiv},
  eprint    = {1711.07656},
  timestamp = {Sun, 03 Dec 2017 12:38:15 +0100},
  biburl    = {http://dblp.org/rec/bib/journals/corr/abs-1711-07656},
  bibsource = {dblp computer science bibliography, http://dblp.org}
}


```








