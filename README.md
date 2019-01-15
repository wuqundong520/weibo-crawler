# Weibo Data Crawling

This is the Python implementation of crawling Weibo data (i.e., posted text, jpg/gif images and videos) of one Weibo user.

The source code (SourceCode_weibocrawler.py) is forked from: https://blog.csdn.net/BF02jgtRS00XKtCx/article/details/79547627.

Notes: We remove the function of crawling comments and add the function of crawling gif images and videos.

# Environment

The code has been tested on **Ubuntu 14.04**. 

# Language

* __Python 3.5 (3.0+)__

# Running

* Empty saving folder (i.e., JuJingyi_Weibo_TI/ or JuJingyi_Weibo_TIV/) before running code!

* To crawl **text** and **jpg images**, excute the following command on Terminal:
```bash
$ python WeiboDataCrawling_TextImage.py
$ # or
$ python3 WeiboDataCrawling_TextImage.py
$ # if both py2 and py3 exist in your operating system.
```
The Weibo data will be saved in JuJingyi_Weibo_TI/ folder.

* To crawl **text**, **jpg images** and **videos**, excute the following command on Terminal:
```bash
$ python WeiboDataCrawling_TextImageVideo.py
$ # or
$ python3 WeiboDataCrawling_TextImageVideo.py
$ # if both py2 and py3 exist in your operating system.
```
The Weibo data will be saved in JuJingyi_Weibo_TIV/ folder.

* To crawl **text**, **jpg/gif images** and **videos**, excute the following command on Terminal:
```bash
$ python WeiboDataCrawling_ALL.py
$ # or
$ python3 WeiboDataCrawling_ALL.py
$ # if both py2 and py3 exist in your operating system.
```
The Weibo data will be saved in JuJingyi_Weibo_ALL/ folder.

# Motivation

XDDD

![Equivariance](https://github.com/HeZhang1994/weibo-data-crawling/blob/master/JuJingyi.jpg)
