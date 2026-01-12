# Nonlocal Operator Identification

## Introduction
This is a sample blog post to demonstrate **Markdown** rendering and **LaTeX** support.

## Mathematical Formulation
We are interested in identifying the kernel $\gamma(x, y)$ in the nonlocal operator:

$$
\mathcal{L}u(x) = \int_{\Omega} (u(y) - u(x))\gamma(x, y) dy
$$

Given data pairs $(u_i, f_i)$ where $\mathcal{L}u_i = f_i$, we can use machine learning techniques to approximate $\gamma$.

## List of Features
- **Bold text** and *Italic text* works!
- Lists are supported:
  1. Item one
  2. Item two

> Blockquotes are also supported for emphasizing key points.

## Code Example
Here is a Python code snippet:

```python
import numpy as np

def f(x):
    return np.sin(x) + 0.1 * np.random.randn(*x.shape)
```
