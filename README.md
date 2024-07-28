# Polygon-Pi
Approximate pi by summing up the change of area of a regular polygon when its edges are doubled.

Equations which the algorithms are derived from:

$$ \beta _{1} = \sqrt{2} $$

$$ \beta _{n} = \sqrt{2 + \beta _{n-1}} $$

$$ \pi = 2 \sqrt{2} + \sum^{\infty}_{n=1} \Big( 2^{n} (2 - \beta _{n+1}) \sqrt{2 - \beta _{n}} \Big) $$
