# Uso de expressão matemática em markdown

## MathJax
### 1
$\sqrt{3x-1}+(1+x)^2$

### 2
$`\sqrt{3x-1}+(1+x)^2`$
  
### 3
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$
  
### 4
```math
\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
```  

### 5
$100/2$


## Katex
https://katex.org/docs/api

### 1
Let $f\colon[a,b]\to\R$ be Riemann integrable. Let $F\colon[a,b]\to\R$ be
$F(x)=\int_{a}^{x} f(t)\,dt$. Then $F$ is continuous, and at all $x$ such that
$f$ is continuous at $x$, $F$ is differentiable at $x$ with $F'(x)=f(x)$.  

### 2
$$
I = \int_0^{2\pi} \sin(x)\,dx
$$