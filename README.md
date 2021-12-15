# List papers on Geometric Deep Learning
Reading papers on Geometric Deep Learning

Contributed by Nhut Nam Le

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#survey-papers">1. Survey</a></td></tr> 
<tr><td colspan="2"><a href="#models">2. Geometric Deep Learning Models</a></td></tr>
<tr>
    <td>&emsp;<a href="#convolutional-neural-networks">2.1 Convolutional Neural Networks</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#group-equivariant-cnns">2.2 Group-equivariant CNNs</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#graph-neural-networks">2.3 Graph Neural Networks</a></td>
</tr>
  <tr>
    <td>&emsp;<a href="#deepsets-transformers-latent-graph-inference">2.4 Deep Sets, Transformers, and Latent Graph Inference</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#equivariant-message-passing-networks">2.5 Equivariant Message Passing Networks</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#intrinsic-mesh-cnns">2.6 Intrinsic Mesh CNNs</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#recurrent-neural-networks">2.7 Recurrent Neural Networks</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#long-short-term-memory-networks">2.8 Long Short-Term Memory networks</a></td>
</tr>
</table>

## [Survey papers](#content)

1. M. M. Bronstein, J. Bruna, Y. LeCun, A. Szlam, and P. Vandergheynst, "Geometric deep learning: going beyond euclidean data," IEEE Signal Processing Magazine, vol. 34, no. 4, pp. 18–42, 2017. [paper](https://arxiv.org/pdf/1611.08097)

2. Z. Zhang, P. Cui, and W. Zhu, "Deep learning on graphs: A survey," arXiv preprint arXiv:1812.04202, 2018. [paper](https://arxiv.org/pdf/1812.04202)

3.  J. Zhou, G. Cui, Z. Zhang, C. Yang, Z. Liu, and M. Sun, "Graph neural networks: A review of methods and applications," arXiv preprint arXiv:1812.08434, 2018. [paper](https://arxiv.org/pdf/1812.08434)

4. Z. Wu, S. Pan, F. Chen, G. Long, C. Zhang, and P. S. Yu, “A comprehensive survey on graph neural networks,” arXiv preprint arXiv:1901.00596, 2019. [paper](https://arxiv.org/pdf/1901.00596)

5. W. Cao, Z. Yan, Z. He and Z. He, "A Comprehensive Survey on Geometric Deep Learning," in IEEE Access, vol. 8, pp. 35929-35949, 2020, doi: 10.1109/ACCESS.2020.2975067. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9003285)

6. Michael M. Bronstein, Joan Bruna, Taco Cohen, Petar Veličković, "Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges". arxiv 2021. [paper](https://arxiv.org/pdf/2104.13478)

## [Geometric Deep Learning Models](#content)

### [Convolutional Neural Networks](#convolutional-neural-networks)
1. Kunihiko Fukushima, "**Neocognitron: A Self-organizing Neural Network Model for a Mechanism of Pattern Recognition Unaffected by Shift in Position**", Springer 1982. [paper](https://www.rctn.org/bruno/public/papers/Fukushima1980.pdf)
2. Yann LeCun, Leon Bottou, Yoshua Bengio, Patrick Haffner, "**Gradient-based learning applied to document recognition**", IEEE 1998. [paper](http://vision.stanford.edu/cs598_spring07/papers/Lecun98.pdf)
3. Jost Tobias Springenberg, Alexey Dosovitskiy, Thomas Brox, Martin Riedmiller, "**Striving for Simplicity: The All Convolutional Net**". arXiv 2014. [paper](https://arxiv.org/pdf/1412.6806)
4. Alex Krizhevsky, Ilya Sutskever, and Geoffrey E Hinton, "**ImageNet Classification with Deep Convolutional Neural Networks**", NIPS 2012. [paper](https://papers.nips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf)
5. Olaf Ronneberger, Philipp Fischer, Thomas Brox, "**U-Net: Convolutional Networks for Biomedical Image Segmentation**", arXiv 2015. [paper](https://arxiv.org/pdf/1505.04597)
6. Sergey Ioffe, Christian Szegedy, "**Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift**", arXiv 2015. [paper](https://arxiv.org/pdf/1502.03167)
7. Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun, "**Deep Residual Learning for Image Recognition**", arXiv 2016. [paper](https://arxiv.org/pdf/1412.6806)
8. Jimmy Lei Ba, Jamie Ryan Kiros, Geoffrey E. Hinton, "**Layer Normalization**", arXiv 2016. [paper](https://arxiv.org/pdf/1607.06450)
9. Tim Salimans, Diederik P. Kingma, "**Weight Normalization: A Simple Reparameterization to Accelerate Training of Deep Neural Networks**", arXiv 2016. [paper](https://arxiv.org/pdf/1602.07868)
10. Dmitry Ulyanov, Andrea Vedaldi, Victor Lempitsky, "**Instance Normalization: The Missing Ingredient for Fast Stylization**", arXiv 2016. [paper](https://arxiv.org/pdf/1607.08022)
11. Tim Cooijmans, Nicolas Ballas, César Laurent, Çağlar Gülçehre, Aaron Courville, "**Recurrent Batch Normalization**", arXiv 2016. [paper](https://arxiv.org/pdf/1603.09025)
12. Yuxin Wu, Kaiming He, "**Group Normalization**", arXiv 2018. [paper](https://arxiv.org/pdf/1803.08494)
13. Shibani Santurkar, Dimitris Tsipras, Andrew Ilyas, Aleksander Madry, "**How Does Batch Normalization Help Optimization?**", arXiv 2018. [paper](https://arxiv.org/pdf/1805.11604)
14. Ting Chen, Simon Kornblith, Mohammad Norouzi, Geoffrey Hinton, "**A Simple Framework for Contrastive Learning of Visual Representations**", arXiv 2020. [paper](https://arxiv.org/pdf/2002.05709)
15. Jean-Bastien Grill, Florian Strub, Florent Altché, Corentin Tallec, Pierre H. Richemond, Elena Buchatskaya, Carl Doersch, Bernardo Avila Pires, Zhaohan Daniel Guo, Mohammad Gheshlaghi Azar, Bilal Piot, Koray Kavukcuoglu, Rémi Munos, Michal Valko, "**Bootstrap your own latent: A new approach to self-supervised Learning**", arXiv 2020. [paper](https://arxiv.org/pdf/2006.07733)
16. Jovana Mitrovic, Brian McWilliams, Jacob Walker, Lars Buesing, Charles Blundell, "**Representation Learning via Invariant Causal Mechanisms**", arXiv 2020. [paper](https://arxiv.org/pdf/2010.07922)
17. Song Mei, Theodor Misiakiewicz, Andrea Montanari, "**Learning with invariances in random features and kernel models**", arXiv 2020. [paper](https://arxiv.org/pdf/2102.13219)

### [Group-equivariant CNNs](#group-equivariant-cnns)
1. Taco S. Cohen, Mario Geiger, Jonas Koehler, Max Welling, "**Spherical CNNs**", arXiv 2018. [paper](https://arxiv.org/pdf/1512.03385)


### [Graph Neural Networks](#graph-neural-networks)

1. Thomas N. Kipf, Max Welling, "**Semi-Supervised Classification with Graph Convolutional Networks**", arXiv 2016. [paper](https://arxiv.org/pdf/1609.02907)
2. Michaël Defferrard, Xavier Bresson, Pierre Vandergheynst, "**Convolutional Neural Networks on Graphs with Fast Localized Spectral Filtering**", arXiv 2016. [paper](https://arxiv.org/pdf/1606.09375)
3. Federico Monti, Davide Boscaini, Jonathan Masci, Emanuele Rodolà, Jan Svoboda, Michael M. Bronstein, "**Geometric deep learning on graphs and manifolds using mixture model CNNs**", arXiv 2016. [paper](https://arxiv.org/pdf/1611.08402)
4. Justin Gilmer, Samuel S. Schoenholz, Patrick F. Riley, Oriol Vinyals, George E. Dahl, "**Neural Message Passing for Quantum Chemistry**", arXiv 2017. [paper](https://arxiv.org/pdf/1704.01212)
5. Petar Veličković, Guillem Cucurull, Arantxa Casanova, Adriana Romero, Pietro Liò, Yoshua Bengio, "**Graph Attention Networks**", arXiv 2018. [paper](https://arxiv.org/pdf/1710.10903)
6. Jiani Zhang, Xingjian Shi, Junyuan Xie, Hao Ma, Irwin King, Dit-Yan Yeung, "**GaAN: Gated Attention Networks for Learning on Large and Spatiotemporal Graphs**", arXiv 2018. [paper](https://arxiv.org/pdf/1803.07294)
7. Peter W. Battaglia, Jessica B. Hamrick, Victor Bapst, Alvaro Sanchez-Gonzalez, Vinicius Zambaldi, Mateusz Malinowski, Andrea Tacchetti, David Raposo, Adam Santoro, Ryan Faulkner, Caglar Gulcehre, Francis Song, Andrew Ballard, Justin Gilmer, George Dahl, Ashish Vaswani, Kelsey Allen, Charles Nash, Victoria Langston, Chris Dyer, Nicolas Heess, Daan Wierstra, Pushmeet Kohli, Matt Botvinick, Oriol Vinyals, Yujia Li, Razvan Pascanu, "**Relational inductive biases, deep learning, and graph networks**", arXiv 2018. [paper](https://arxiv.org/pdf/1806.01261)
8. Felix Wu, Tianyi Zhang, Amauri Holanda de Souza Jr., Christopher Fifty, Tao Yu, Kilian Q. Weinberger, "**Simplifying Graph Convolutional Networks**", arXiv 2019. [paper](https://arxiv.org/pdf/1902.07153)

### [Deep Sets, Transformers, and Latent Graph Inference](#deepsets-transformers-latent-graph-inference)
1. Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Lukasz Kaiser, Illia Polosukhin, "**Attention Is All You Need**", arXiv 2017. [paper](https://arxiv.org/pdf/1706.03762)
2. Manzil Zaheer, Satwik Kottur, Siamak Ravanbakhsh, Barnabas Poczos, Ruslan Salakhutdinov, Alexander Smola, "**Deep Sets**", arXiv 2018. [paper](https://arxiv.org/pdf/1706.03762)

### [Equivariant Message Passing Networks](#equivariant-message-passing-networks)
1. Victor Garcia Satorras, Emiel Hoogeboom, Max Welling, "**E(n) Equivariant Graph Neural Networks**", arXiv 2021. [paper](https://arxiv.org/pdf/2102.09844)

### [Intrinsic Mesh CNNs](#intrinsic-mesh-cnns)

**Geodesic patches**
1. Ron Kimmel, James A Sethian. **Computing geodesic paths on manifolds**, [paper](https://math.berkeley.edu/~sethian/2006/Papers/sethian.kimmel.geodesics.pdf)
2. Iasonas Kokkinos, Michael M Bronstein, Roee Litman, Alex M Bronstein, **Intrinsic shape context descriptors for deformable shapes**, [paper](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.665.274&rep=rep1&type=pdf)
3. Jonathan Masci, Davide Boscaini, Michael M. Bronstein, Pierre Vandergheynst, **Geodesic convolutional neural networks on Riemannian manifolds**, arXiv 2015. [paper](https://arxiv.org/pdf/1501.06297)

**Isotropic filters**

**Fixed gauge**

**Angular pooling**

**Gauge-equivariant filters**

### [Recurrent Neural Networks](#recurrent-neural-networks)

### [Long Short-Term Memory networks](#long-short-term-memory-networks)

**Status**: Still updating...


