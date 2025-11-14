---
layout: default
title: Self-similarity
permalink: /SS/
---

# Introduction 
When I think of self-similarity, the first thing that comes to my mind is Romanesco broccoli. The shape is indeed self-similar and mathematically closely related to a spiral. In simple words, self-similar means that no matter how much you zoom in, you will see the same shape. This thinking can then be applied not only to shapes (sets, functions), but also to equations. 

# Self-similarity of shapes/functions
Formally, a function $f(x)$ or a set $S$ is self-similar if scaling the input by a factor $\lambda$ changes the output in a predictable, proportional way:

$$
f(\lambda x) = \lambda^k f(x),
$$

where $k$ is a scaling exponent. Here are some intuitive real-world examples, some of which I am sure all of us have seen somewhere. 

This is a standard definition of a homogeneous function of degree $k$ that we learn in Calculus. A simple example is that of a pyramid shape 

$
f(x,y) = (|x|+|y|)
$

The function is homogeneous of degree 1, and the level sets are given by

$|x|+|y|=c$.

and 

$
|2x|+|2y|=c \implies |x|+|y|=c/2$ 

This means that if you look at the pyramid from the top (along the $z$-axis) and zoom in by twice, you will see the same square shape with half the side-length.  


# Self-similarity of equations
