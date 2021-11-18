---
title: "Attention is all you need"
excerpt: "Trying different attention functions for Transformer model"
collection: portfolio
---

* Replicated "Attention is all you need" paper
* Redesigned the architecture by changing attention scoring function to observe difference between different attention functions [Tensorflow ]
* Trained and tested on WMT14  English-German dataset
* Out of the three functions, the scaled dot product attention, the function used in the original paper, had the best performance in both the case sensitive (21.8 BLEU) and case insensitive (22.3 BLEU) areas on the WMT14 English-German test set after training 100000 steps or 12 hours on a single GPU (K80).
