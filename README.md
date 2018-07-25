# swagaf
SWAG dataset. Currently, this belongs to a paper that is in submission to EMNLP 2018.

## Setting this up
you'll need to install a bunch of things. I listed my specs if that helps in `requirements.txt`. The most important thing probably is that I'm using python 3.6, and pytorch 3.1. The following commands will set up the version of allennlp that I used.

``` 
git clone https://github.com/allenai/allennlp.git
cd allennlp    
git checkout 7142962d330ca5a95cade114c26a361c78f2042e
INSTALL_TEST_REQUIREMENTS="true" ./scripts/install_requirements.sh
python setup.py install
```


Also, for everything in this repo, you'll want to ```export PYTHONPATH=/home/rowan/code/swagaf```



## Common use cases

The data is all in `data/`, baseline and instructions are in `swag_baselines`. Most people will not need to look at `create_swag` or `raw_data` but it's there if you need it!