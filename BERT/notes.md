* traditional DL that beat TFIDF
![](images/1.png)
* word2vec embeddings. embeddings learnt unsupervised manner
![](images/2.png)
* LSTM can't exploit GPU parallelization they way CNN does
![](images/3.png)
![](images/4.png)
* New in DL NLP-
![](images/5.png)
* Dealing with out of vocabulary words-
  * https://github.com/google/sentencepiece
  * https://www.aclweb.org/anthology/D18-2012.pdf
  * ![](images/6.png)
* Attention is all you need. CNN based method
  * ![](images/7.png)
* Language models
  * Like embeddings, now train entire model on huge text corpus. Idea is to capture good context
  * Trains both model and embeddings in **unsupervised way**
  * All this can be done for free (unsupervised) and captures a lot of useful information
  * ![](images/8.png)
* Fine Tuning. Made popular by fast.ai
  * ![](images/9.png)
  * ![](images/10.png)
* BERT
  * successor to ELMo
  * ![](images/11.png)
  * Full of transformers
  * ![](images/12.png)
  * SQUAD is QA task
  * imageNet moment for NLP. Allows amazing transfer learning
  * Beat others by huge margins. See the original paper of BERT
  * Large BERT is mainly for TPU size.
  * Expensive to train from scratch
  * ![](images/13.png)
  * ![](images/14.png)
