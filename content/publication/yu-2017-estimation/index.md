---
title: "Estimation of a Low-rank Topic-Based Model for Information Cascades"
date: 2017-09-06
publishDate: 2020-01-27T20:57:22.567158Z
authors: ["Ming Yu", "Varun Gupta", "Mladen Kolar"]
publication_types: ["2"]
abstract: "We consider the problem of estimating the latent structure of a social network based on the observed information diffusion events, or ıt cascades. Here for a given cascade, we only observe the times of infection for infected nodes but not the source of the infection. Most of the existing work on this problem has focused on estimating a diffusion matrix without any structural assumptions on it. In this paper, we propose a novel model based on the intuition that an information is more likely to propagate among two nodes if they are interested in similar topics which are also prominent in the information content. In particular, our model endows each node with an influence vector (which measures how authoritative the node is on each topic) and a receptivity vector (which measures how susceptible the node is for each topic). We show how this node-topic structure can be estimated from the observed cascades and prove an analytical upper bound on the estimation error. The estimated model can be used to build recommendation systems based on the receptivity vectors, as well as for marketing based on the influence vectors. Experiments on synthetic and real data demonstrate the improved performance and better interpretability of our model compared to existing state-of-the-art methods."
featured: false
publication: "*To appear in JMLR*"
tags: ["stat.ML", "cs.LG", "cs.SI"]
---

