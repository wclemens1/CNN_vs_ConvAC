# Comparison of CNN and ConvAC

While reading around the subject of deep learning I started to look for links between the field and AdS/CFT, my field of study for my PhD. Among other attempts to make this connection I found https://arxiv.org/abs/1704.01552 which posits a relation between the tensor networks used in condensed matter physics and "ConvACs" a variation on convolutional neural networks with linear activations and nonlinearity introduced by product pooling that the authors had previously introduced in https://arxiv.org/abs/1509.05009.

In order to understand this technique better, mostly so I can judge the plausibility of the connection to physics, I decided to implement a simple ConvAC and compare it's performance to an equivalent CNN on a simple problem: the MINST dataset.

It should be noted that the papers in question are very theoretical and this notebook comprises my messing around to try and understand them rather than an attempt to replicate a specific result