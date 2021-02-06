---
layout: page
title: Modern Hopfield Networks
description:
img: /assets/img/hopfield/hopfieldRetrieval_homer.svg
importance: 3
---

One goal of deep learning is to provide models with the ability to store and access information in a learnable manner. A classical example of this are Hopfield Networks. These networks are capable of storing information and retrieving it by association. However, their limited capacity and the restriction to binary data render them inadequate in the context of modern deep learning. Recent work has led to a novel formulation of Hopfield Networks which exhibit considerable increase in storage capacity. However, in order to integrate these modern Hopfield networks into deep learning architectures, it is necessary to make them differentiable, which in turn requires a transition from the binary to the continuous domain.

 In the paper "Hopfield Networks is all you need" we introduce a continuous generalization of modern Hopfield Networks. This includes a novel energy function for continuous patterns and a new update rule which ensures global convergence to stationary points of the energy (local minima or saddle points). Both desirable properties, the exponential storage capacity as well as the fast convergence of the update rule, are inherited from their binary counterparts. Here, fast convergence typically means convergence after one update step, which corresponds to one forward pass. This opens up the possibility to integrate continuous modern Hopfield Networks as layers into deep learning architectures.

This ability results in a wide variety of novel architectures and use cases for deep learning. The task of this group is to explore the new possibilities opening up as well as advance the understanding of this new form of Hopfield Networks.   


<div class="publications">
<h4>recent publications in Modern Hopfield Networks:</h4>
  {% bibliography -f papers -q @*[category=hopfield]*%}
</div>
