---
author: Paras Mittal
mathjax: true
---

Here are two false math proofs. I hope to find more subtle ones as most people spot the err in these.

This first one is rather obvious and fools no one. You can vary it by using say 2 separate variables \\(x\\) and \\(y\\) which are equal and then dividing by \\(x-y\\) on the 3rd line to make the divide by 0 error less conspicuous.

$$
\begin{align}
x^2 - x^2 &= x^2 - x^2\\
\implies (x-x)(x+x) &= x(x-x) &\text{Difference of squares and factoring} \\
\implies x+x &= x &\text{Divide by \(x\)} \\
\end{align}
$$

This one is slightly trickier, as it does not rely on the infamous divide by 0.

$$
\begin{align}
i &= i^{4 \over 4} \\
&= \sqrt[4]{i^4} \\
&= \sqrt[4]{1} \\
&= 1 \\
\end{align}
$$
