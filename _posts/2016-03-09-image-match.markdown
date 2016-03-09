---
published: true
title: image-match
layout: post
---
We've just open-sourced one of my main projects at ascribe!  You can check it out [here](https://github.com/ascribe/image-match).

image-match is a simple package for finding approximate image matches from a
corpus.  It is similar, for instance, to [pHash](http://www.phash.org/), but
includes a database backend that easily scales to billions of images and
supports sustained high rates of image insertion: up to 10,000 images/s on our
cluster!

Based on the paper [_An image signature for any kind of image_, Goldberg et
al](http://www.cs.cmu.edu/~hcwong/Pdfs/icip02.ps).  There is an existing
[reference implementation](https://www.pureftpd.org/project/libpuzzle) which
may be more suited to your needs.

