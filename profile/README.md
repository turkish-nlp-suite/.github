![nlp suite banner](/profile/nlp-suite-banner2.png)

:wave: Welcome to Turkish NLP Suite! 
======

[Turkish NLP Suite](https://www.turkish-nlp-suite.com) is a non-profit organization dedicated to Turkish NLP. We create open source corpora, pretrained models, code , tutorials and all types of linguistic resources for Turkish natural language processing. All of our code is cutting-edge, our models are easy to install and use, tutorials are great to get started .. This is state-of-art Turkish NLP after all.

:boom: We :heart: spaCy
=====
That's true, we love [spaCy](https://spacy.io/) because of the blazing fast code, great architecture, flexible pipelining, detailed documentation and awesome ecosystem. We proudly present spaCy Turkish models:

- tr_core_web_md
- tr_core_web_lg
- tr_core_web_trf  

All pipelines contains a tokenizer, trainable lemmatizer, POS tagger, dependency parser, morphologizer and NER components. You can find out more about each model in the [dedicated repo](https://github.com/turkish-nlp-suite/turkish-spacy-models) and download the models from [HuggingFace](https://huggingface.co/turkish-nlp-suite).

spaCy Turkish models comes with comprehensive tutorials and code. Please visit the documentation section for the details.
 
:sunglasses: We love cutting edge NLP
====
We corporate modern techniques into all our work including transformers, GPU computing as well as using the most efficient data structures. For some examples, the brand new Turkish spaCy model `tr_core_web_trf` is a transformer based pipeline; mini project "Quick FAQ Chatbot" integrates `sentence-transformers` and more.

:blue_book:  We love compiling datasets
====
Modern NLP revolves around data, hence labelled data (even in the msall amounts) are crucial for improving quality of many NLP tasks. As a result, compiling and serving Turkish datasets lies at the core of Turkish NLP Suite project. All of our datasets are presented with a commercial licence, completely open-source and ready to use. We also use our datasets in our projects and tutorials.
Here's a list of our datasets:

* [Corona-mini](https://github.com/turkish-nlp-suite/Corona-mini-dataset) : A mini corpus of Turkish social media reviews about Corona symptoms.
* [ATIS Turkish](https://github.com/turkish-nlp-suite/Atis_Turkish): A multi-purpose NLU dataset for Turkish, including entities and slots.
* [Turkish Wiki NER Dataset](https://github.com/turkish-nlp-suite/Turkish-Wiki-NER-Dataset): A general purpose Turkish NER Dataset with fine labels.
* [Vitamins and Supplements NER and Span Dataset](https://github.com/turkish-nlp-suite/Vitamins-Supplements-NER-dataset): A Turkish NER dataset that lies in intersection of medical NLP and product reviews.
* [Vitamins and Supplements Reviews](https://github.com/turkish-nlp-suite/Vitamins-Supplements-NER-dataset): A sentiment analysis dataset for Turkish, that lies in intersection of medical NLP and customer sentiment.
* [Beyazperde Top 300 Movies Dataset](https://github.com/turkish-nlp-suite/BeyazPerde-Movie-Reviews): Turkish sentiment analysis dataset of Top 300 Movies reviews.
* [Beyazperde Top All Movies Dataset](https://github.com/turkish-nlp-suite/BeyazPerde-Movie-Reviews): Turkish sentiment analysis dataset from movie reviews.

For the details and data please visit the dedicated repos of the datasets.
We also provide guidance and documentations for the ones who would like to compile their own datasets. If you're looking for creating your own datasets, please visit the documentation section.

:construction_worker: We love mining our datasets
====
Surely we like to mine some good Turkish datasets :wink: If you'd like to do some data mining together, you can have a look at our video series [Quick recipes with spaCy Turkish](https://www.youtube.com/watch?v=w0WCkgCOzzw&list=PLJTHlIwB8VcoWxYHnsZOQCxWOraW42NBj) and [Quick FAQ Bot](https://www.youtube.com/watch?v=LUYiRfysnjY&list=PLJTHlIwB8Vcr0KHTcRRRFa3QMcI4F4lW5); or even better read the Medium blog post about [how sentiment turned into political heat after earthquake disaster](https://medium.com/p/ce65ece62aea).

🧠 We provide large corpora
====
We compile and open source large-scale Turkish datasets for model training purposes. We proudly present **BellaTurca**, first big-scale, diverse and high quality data collection for Turkish. For more details, please visit the dataset [HF repo](https://huggingface.co/datasets/BayanDuygu/BellaTurca).

Another dataset for model building is a large-scale instructions dataset for Turkish, [InstructTurca](https://huggingface.co/datasets/turkish-nlp-suite/InstrucTurca). This dataset contains translates of popular instruction tuning datasets such as OpenOrca and MedText...

:movie_camera: We love documentation: Turkish NLP Youtube Channel
====
If you like doing some pair programming, please visit our [Turkish NLP Youtube channel](https://www.youtube.com/@NLPwithDuygu/playlists). Here's a list of playlists:

* [Veriseti formatları](https://www.youtube.com/watch?v=iAsCz1kk2Oc&list=PLJTHlIwB8VcoetgeXaSGJZ0l65DRx1wne)
* [Veriseti nasıl derlenir](https://www.youtube.com/watch?v=XNYq58eMsgY&list=PLJTHlIwB8Vco4ONU_mCNOYIcVyFA9QrBr)
* [Baştan sona Türkçe Linguistik](https://www.youtube.com/watch?v=ZiArCDOuNVo&list=PLJTHlIwB8Vcqltlhbmsc12Srthv73OeOF)
* [spaCy ve Semantic Search'le hızlı FAQ Botu](https://www.youtube.com/watch?v=LUYiRfysnjY&list=PLJTHlIwB8Vcr0KHTcRRRFa3QMcI4F4lW5)
* [Hızlı spaCy Türkçe tarifleri]( https://www.youtube.com/watch?v=w0WCkgCOzzw&list=PLJTHlIwB8VcoWxYHnsZOQCxWOraW42NBj)
* [spaCy modeli nasıl yapılır?](https://www.youtube.com/watch?v=dTdpRP-t920&list=PLJTHlIwB8Vcp_1b1eFwKcKKmzfs16EFtH)
* [Semantic Web](https://www.youtube.com/watch?v=rLaI7Zr7bzU&list=PLJTHlIwB8Vcp_amsALcxd5UvawDG0062x)

Get started
====
There are several paths to get started indeed. If you're already working with text and speech data, you can dive into Turkish only parts safely. This path includes information about Turkish linguistics, then application code. One can watch 
* All about Turkish linguistics
* Quick recipes with spaCy Turkish
* Quick FAQ Bot
* How to train spaCy models
* Semantic Web  

If you're a junior/student or didn't work on NLP problems before, we suggest starting from the beginning. This path includes the foundational series "NLP dataset formats" and "How to compile NLP datasets". After warming up to NLP tasks and data conventions, you can dive inot the most advanced parts above :wink:

Hugging Face Repo
====
All our models, datasets and corpora can be found under [Turkish NLP Suite HF repo](https://huggingface.co/turkish-nlp-suite).

Project Blog
====
Don't forget to visit our project blog for project stories, code and more: [Blog for best of Turkish NLP](https://turkish-nlp-suite.github.io/)

Medium Blog Posts
====
* [Turkish NLP, a Gentle Introduction](https://medium.com/p/2b33e694dd78)
* [Turkish Phonetics: A Quick Intro](https://medium.com/p/cf75bb7eec79)
* [Neden yasaklandı? Depremle ilgili Ekşi Sözlük yorumlarına NLP gözüyle bakış](https://medium.com/p/ce65ece62aea)
* [A collection of brand new datasets for Turkish NLP](https://medium.com/p/fc83ca3c95df)
* [Brand new spaCy Turkish models](https://medium.com/google-developer-experts/brand-new-spacy-turkish-models-304da649eacc)
* [Quick recipes with spaCy Turkish: How is your infection doing?](https://medium.com/google-developer-experts/quick-recipes-with-spacy-turkish-how-is-your-infection-doing-4ee1421b2443)
* [InstrucTurca: An open source instruction tuning dataset for Turkish](https://medium.com/google-developer-experts/instructurca-an-open-source-instruction-tuning-dataset-for-turkish-18c37b0e99b9)
  
Publications
====
* [Bella Turca: A Large-Scale Dataset of Diverse Text Sources for Turkish Language Modeling](https://link.springer.com/chapter/10.1007/978-3-031-70563-2_16)
* [Gender Bias in Turkish Word Embeddings: A Comprehensive Study of Syntax, Semantics and Morphology Across Domains](https://aclanthology.org/2024.gebnlp-1.13.pdf)
* [A Diverse Set of Freely Available Linguistic Resources for Turkish](https://aclanthology.org/2023.acl-long.768/)
* [A Statistical Approach to Analyzing Turkish Morphology](https://link.springer.com/chapter/10.1007/978-3-031-09909-0_12)

  
**Google ML Developer Programs team supported this work by providing Google Cloud Credit. Many thanks to Google Developer Experts programme for their generous contributions!**

