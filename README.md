formal-weyl
===========
The algebra for formal power series in elements of the Weyl algebra.

In particular it allows Taylor expansions of expressions like exp(z*(a^2-a'^2)/2) where a and a' don't commute and [a,a']=1.

The Examples
------------
* Example0: Wick's theorem and wiring diagrams
* Example1: Bernoulli numbers and Euler-Maclaurin summation
* Example2: Umbral calculus with Laguerre and Hermite polynomials
* Example3: Example from QM - properties of squeezed states
* Example4: Investigating various rational functions of X and D

Many of these results can be explained by "Combinatorial Models of Creation-Annihilation", Blasiak & Flajolet
https://arxiv.org/abs/1010.0354

Status
------
This is a completed project, but incomplete code. The code isn't perfect but it allowed me to perform certain computations I wanted to experiment with.

Some things that could be improved
* format of output
* division is (of course) a partial function. In this case we have left-division and right-division and I haven't made any effort to characterise when exactly a division is valid.
* Showing two series share the first few coefficients isn't a proof that the series are equal. Except it is(!!!) if you can prove some other properties first. Maybe one day I'll do this. See https://en.wikipedia.org/wiki/Holonomic_function
