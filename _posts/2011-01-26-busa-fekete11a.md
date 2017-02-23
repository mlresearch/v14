---
title: Ranking by calibrated AdaBoost
abstract: This paper describes the ideas and methodologies that we used in the Yahoo
  learning-to-rank challenge^1. Our technique is essentially pointwise with a listwise
  touch at the last combination step. The main ingredients of our approach are 1)
  preprocessing (querywise normalization) 2) multi-class AdaBoost.MH 3) regression
  calibration, and 4) an exponentially weighted forecaster for model combination.
  In post-challenge analysis we found that preprocessing and training AdaBoost with
  a wide variety of hyperparameters improved individual models significantly, the
  final listwise ensemble step was crucial, whereas calibration helped only in creating
  diversity.
pdf: http://jmlr.org/proceedings/papers/v14/busa-fekete11a/busa-fekete11a.pdf
layout: inproceedings
id: busa-fekete11a
month: 0
firstpage: 37
lastpage: 48
page: 37-48
sections: 
author:
- given: R.
  family: Busa-Fekete
- given: B.
  family: Kégl
- given: T.
  family: "Éltető"
- given: G.
  family: Szarvas
reponame: v14
date: 2011-01-26
address: Haifa, Israel
publisher: PMLR
container-title: Proceedings of the Learning to Rank Challenge
volume: '14'
genre: inproceedings
issued:
  date-parts:
  - 2011
  - 1
  - 26
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
