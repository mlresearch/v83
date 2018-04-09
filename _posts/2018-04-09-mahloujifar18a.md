---
title: Learning under $p$-Tampering Attacks
abstract: "Recently, Mahloujifar and Mahmoody (TCC’17) studied attacks against learning
  algorithms  using a special case of Valiant’s malicious noise, called $p$-tampering,
  \ in which the adversary gets to change any training example with independent probability
  $p$ but  is limited to only choose ‘adversarial’ examples with correct labels. They
  obtained $p$-tampering attacks that increase the error probability in the so called
  ‘targeted’ poisoning model in which the adversary’s goal is to increase the loss
  of the trained hypothesis over a particular test example. At the heart of their
  attack was an efficient algorithm to bias the average output of any bounded real-valued
  function through $p$-tampering. \r In this work, we present new biasing attacks
  for biasing the average output of bounded real-valued functions. Our new biasing
  attacks achieve in \\emph{polynomial-time} the the best bias  achieved by MM16 through
  an \\emph{exponential} time $p$-tampering attack.  Our improved biasing attacks,
  directly imply improved $p$-tampering attacks against learners in the targeted poisoning
  model. As a bonus, our attacks come with considerably simpler analysis compared
  to previous attacks.  \r We also  study the possibility of PAC learning under $p$-tampering
  attacks in the \\emph{non-targeted} (aka indiscriminate) setting where the adversary’s
  goal is  to increase the risk of the generated hypothesis (for a random test example).
  We show that PAC learning is  \\emph{possible} under $p$-tampering poisoning attacks
  essentially whenever it is possible in the realizable setting without the attacks.
  We further show that PAC learning  under ‘no-mistake’ adversarial noise is \\emph{not}
  possible, if the adversary could choose the (still limited to only $p$ fraction
  of) tampered examples that  she substitutes with adversarially chosen ones. Our
  formal model for such ‘bounded-budget’ tampering attackers is  inspired by the notions
  of (strong) adaptive corruption in secure multi-party computation."
layout: inproceedings
series: Proceedings of Machine Learning Research
id: mahloujifar18a
month: 0
tex_title: Learning under $p$-Tampering Attacks
firstpage: 572
lastpage: 596
page: 572-596
order: 572
cycles: false
author:
- given: Saeed
  family: Mahloujifar
- given: Dimitrios I.
  family: Diochnos
- given: Mohammad
  family: Mahmoody
date: 2018-04-09
address: 
publisher: PMLR
container-title: Proceedings of Algorithmic Learning Theory
volume: '83'
genre: inproceedings
issued:
  date-parts:
  - 2018
  - 4
  - 9
pdf: http://proceedings.mlr.press/v83/mahloujifar18a/mahloujifar18a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
