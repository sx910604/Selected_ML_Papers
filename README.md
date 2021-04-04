# Selected Machine Learning Papers
[![Badge](https://img.shields.io/badge/link-996.icu-%23FF4D5B.svg?style=flat-square)](https://996.icu/#/en_US)

This is a collection of selected machine learning papers I read as a data scientist. The collections mainly includes papers of influential machine learning approaches which may be beyond the scope of machine learning courses or may not appear in machine learning textbook. 

Please feel free to comment and provide suggestions. 

The list is for study purpose only. If any author does not want the paper be listed, please contact xiangshen@gwu.edu. 


***

## Table of Content
* [Classic Machine Learning](https://github.com/sx910604/Selected_ML_Papers#Classic-Machine-Learning)
* [Deep Learning](https://github.com/sx910604/Selected_ML_Papers#Deep-Learning)
* [Recommender System](https://github.com/sx910604/Selected_ML_Papers#Recommender-System)
* [Natural Language Processing](https://github.com/sx910604/Selected_ML_Papers#Natural-Language-Processing)
* [Computer Vision](https://github.com/sx910604/Selected_ML_Papers#Computer-Vision)
* [Blogs](https://github.com/sx910604/Selected_ML_Papers#Blogs)

***

## Classic Machine Learning
* **LightGBM** Ke, Guolin, et al. "Lightgbm: A highly efficient gradient boosting decision tree." Advances in neural information processing systems 30 (2017): 3146-3154.
* **Xgboost** Chen, Tianqi, and Carlos Guestrin. "Xgboost: A scalable tree boosting system." Proceedings of the 22nd acm sigkdd international conference on knowledge discovery and data mining. 2016.
* **SMOTE** Chawla, Nitesh V., et al. "SMOTE: synthetic minority over-sampling technique." Journal of artificial intelligence research 16 (2002): 321-357.
* **Bayesian Optimization** Snoek, Jasper, Hugo Larochelle, and Ryan P. Adams. "Practical bayesian optimization of machine learning algorithms." arXiv preprint arXiv:1206.2944 (2012).
* **t-SNE** Van der Maaten, Laurens, and Geoffrey Hinton. "Visualizing data using t-SNE." Journal of machine learning research 9.11 (2008).
* **Shap** Lundberg, Scott M., Gabriel G. Erion, and Su-In Lee. "Consistent individualized feature attribution for tree ensembles." arXiv preprint arXiv:1802.03888 (2018).
* **LIME** Ribeiro, Marco Tulio, Sameer Singh, and Carlos Guestrin. "" Why should i trust you?" Explaining the predictions of any classifier." Proceedings of the 22nd ACM SIGKDD international conference on knowledge discovery and data mining. 2016.
* **CRF** Lafferty, John, Andrew McCallum, and Fernando CN Pereira. "Conditional random fields: Probabilistic models for segmenting and labeling sequence data." (2001).
***

## Deep Learning
* Srivastava, Nitish, et al. "Dropout: a simple way to prevent neural networks from overfitting." The journal of machine learning research 15.1 (2014): 1929-1958.
* He, Kaiming, et al. "Delving deep into rectifiers: Surpassing human-level performance on imagenet classification." Proceedings of the IEEE international conference on computer vision. 2015.
* Ioffe, Sergey, and Christian Szegedy. "Batch normalization: Accelerating deep network training by reducing internal covariate shift." International conference on machine learning. PMLR, 2015.
* Ba, Jimmy Lei, Jamie Ryan Kiros, and Geoffrey E. Hinton. "Layer normalization." arXiv preprint arXiv:1607.06450 (2016).
* Kingma, Diederik P., and Jimmy Ba. "Adam: A method for stochastic optimization." arXiv preprint arXiv:1412.6980 (2014).
* **SWA** Izmailov, Pavel, et al. "Averaging weights leads to wider optima and better generalization." arXiv preprint arXiv:1803.05407 (2018).


***

## Recommender System
* Rendle, Steffen. "Factorization machines." 2010 IEEE International Conference on Data Mining. IEEE, 2010.

***

## Natural Language Processing
### Word Representation
* Mikolov, Tomas, et al. "Efficient estimation of word representations in vector space." arXiv preprint arXiv:1301.3781 (2013).
* Mikolov, Tomas, et al. "Distributed representations of words and phrases and their compositionality." arXiv preprint arXiv:1310.4546 (2013).
* **Glove** Pennington, Jeffrey, Richard Socher, and Christopher D. Manning. "Glove: Global vectors for word representation." Proceedings of the 2014 conference on empirical methods in natural language processing (EMNLP). 2014.

### RNN Structure
* Hochreiter, Sepp, and Jürgen Schmidhuber. "Long short-term memory." Neural computation 9.8 (1997): 1735-1780.
* Chung, Junyoung, et al. "Empirical evaluation of gated recurrent neural networks on sequence modeling." arXiv preprint arXiv:1412.3555 (2014).

### Sentence Representation
* Le, Quoc, and Tomas Mikolov. "Distributed representations of sentences and documents." International conference on machine learning. PMLR, 2014.
* Kiros, Ryan, et al. "Skip-thought vectors." arXiv preprint arXiv:1506.06726 (2015).
* Iyyer, Mohit, et al. "Deep unordered composition rivals syntactic methods for text classification." Proceedings of the 53rd annual meeting of the association for computational linguistics and the 7th international joint conference on natural language processing (volume 1: Long papers). 2015.
* Riedel, Benjamin, et al. "A simple but tough-to-beat baseline for the Fake News Challenge stance detection task." arXiv preprint arXiv:1707.03264 (2017).
* InferSent
* Quick thoughts
* Universal Sentence Encoder

### Subword
* **BPE** Sennrich, Rico, Barry Haddow, and Alexandra Birch. "Neural machine translation of rare words with subword units." arXiv preprint arXiv:1508.07909 (2015).
* **Wordpiece** Wu, Yonghui, et al. "Google's neural machine translation system: Bridging the gap between human and machine translation." arXiv preprint arXiv:1609.08144 (2016).
* **UniLM** Kudo, Taku. "Subword regularization: Improving neural network translation models with multiple subword candidates." arXiv preprint arXiv:1804.10959 (2018).

### Attention and Transformer
* Bahdanau, Dzmitry, Kyunghyun Cho, and Yoshua Bengio. "Neural machine translation by jointly learning to align and translate." arXiv preprint arXiv:1409.0473 (2014).
* Vaswani, Ashish, et al. "Attention is all you need." arXiv preprint arXiv:1706.03762 (2017).


### CNN
* Gehring, Jonas, et al. "Convolutional sequence to sequence learning." International Conference on Machine Learning. PMLR, 2017.
* Convolutional Neural Networks for Sentence Classification 
* Ma, Xuezhe, and Eduard Hovy. "End-to-end sequence labeling via bi-directional lstm-cnns-crf." arXiv preprint arXiv:1603.01354 (2016).
* 

### BERT and related
* Elmo
* BERT
* UniLM
* ERNIE
* PRADO
* TinyBERT
* ALBERT
* RoBert
* DistBERT
* pQRNN

### Multi-task learning
* MTDNN
* BERT Pals

### Model Calibration
* Guo, Chuan, et al. "On calibration of modern neural networks." International Conference on Machine Learning. PMLR, 2017.
* Szegedy, Christian, et al. "Rethinking the inception architecture for computer vision." Proceedings of the IEEE conference on computer vision and pattern recognition. 2016.
* Müller, Rafael, Simon Kornblith, and Geoffrey Hinton. "When does label smoothing help?." arXiv preprint arXiv:1906.02629 (2019).

### Misc
* Joulin, Armand, et al. "Bag of tricks for efficient text classification." arXiv preprint arXiv:1607.01759 (2016).
* Guo, Chuan, et al. "On calibration of modern neural networks." International Conference on Machine Learning. PMLR, 2017.
* **seq2seq** Sutskever, Ilya, Oriol Vinyals, and Quoc V. Le. "Sequence to sequence learning with neural networks." arXiv preprint arXiv:1409.3215 (2014).
***

## Computer Vision


***

## Blogs
* Expedia Group Tech Blog https://medium.com/expedia-group-tech
* Bookings Tech Blog https://blog.booking.com/
* Ctrip Tech https://zhuanlan.zhihu.com/ctriptech  (Chinese)
* Amazon Science Blog https://www.amazon.science/blog
* AWS Machine Learning https://aws.amazon.com/blogs/machine-learning/
* Facebook AI Blog https://ai.facebook.com/blog
* Google AI Blog https://ai.googleblog.com/
* OpenAI Blog https://openai.com/blog/
* Netflex Tech Blog https://netflixtechblog.com/
* Uber Engineering Blog https://eng.uber.com/
* Lyft Engineering Blog https://eng.lyft.com/
* Quore Engineering Blog https://www.quora.com/q/quoraengineering
* Airbnb Engineering and Data Science Blog https://medium.com/airbnb-engineering/tagged/data-science
* DeepMind Blog https://deepmind.com/blog
* Pinterest Engineering Blog https://medium.com/pinterest-engineering/machine-learning/home
* Linkedin Engineering Blog https://engineering.linkedin.com/blog
* CMU ML Blog https://blog.ml.cmu.edu/
* BAIR Blog https://bair.berkeley.edu/blog/
* Stanford AI Lab Blog http://ai.stanford.edu/blog/
* Meituan Tech https://tech.meituan.com/ (Chinese)

***
