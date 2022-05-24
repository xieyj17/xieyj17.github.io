---
layout: post
title:  "Probabilistic Machine Learning, Vol 1, Ch 4, Statistics"
date:   9022-05-20 00:00:00 -0400
categories: jekyll update
---

# 1. A little spoiler for Entropy and Kullback Leibler divergence

## KL divergence to NLL
For (4.16), identify function is easier to understand than delta function.

$p_D(x,y) = 1/N$ if (x,y) has support, and 0 otherwise.

(4.19) means minimizing NLL leads to smallest KL distrance from the empirical distribution $q(y|x)$ true distribtuion $p_{D}(y|x)$