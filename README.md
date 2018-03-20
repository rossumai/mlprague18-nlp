# Deep Learning for Text Processing Workshop at Machine Learning Prague 2018

## Instructions for attendees of NLP workshop:
* Please come with a working Python installation that includes:
  * Jupyter notebook server
  * Packages: Tensorflow (1.5.0; GPU not required!), Keras (2.1.5), NLTK (3.2.5)
  * Detailed instructions:
    * Linux, MacOSX:
      * create a Python virtual environment by running the following in terminal:
        * pip install virtualenv
        * virtualenv --system-site-packages pymlprague
        * source pymlprague/bin/activate
        * pip install tensorflow==1.5.0 keras==2.1.5 nltk==3.2.5 jupyter
    * MacOSX, Windows:
      * If you don’t have Python installed you can download and install Anaconda: https://conda.io/docs/user-guide/install/index.html
      * You can then create a virtual environment with command line:
        * conda create -n pymlprague tensorflow=1.5.0 keras=2.1.5 nltk=3.2.5 jupyter
        * source activate pymlprague
    * You can find detailed steps for Keras and Tensorflow under the following links, just in case:
        * https://keras.io/#installation
        * https://www.tensorflow.org/install/
  * (Note that we will assume basic familiarity with Python.)
* Download big data required for the experiments you will be doing:
  * https://nlp.stanford.edu/data/glove.6B.zip
  * http://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz
  * python -m nltk.downloader semcor punkt perluniprops

## Tutorials:
* Movie Reviews Sentiment Classification: **IMDB Sentiment.ipynb**
* Capital Letters Recognition: **uppercase.ipynb**

