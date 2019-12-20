Rates of Convergence for Sparse Variational Gaussian Process Regression
----------
<br>by David R. Burt (University of Cambridge, Cambridge, UK) Carl Edward Rasmussen (University of Cambridge, Cambridge, UK )<br>
Mark van der Wilk (PROWLER.io, Cambridge, UK)
<br>PMLR  2019<br>
`Abstract`:<br>
Excellent variational approximations to Gaussian process posteriors have been developed which avoid the O(N3) scaling with dataset size N. They reduce the computational cost to O(NM2), with M≪N the number of inducing variables, which summarise the process. While the computational cost seems to be linear in N, the true complexity of the algorithm depends on how M must increase to ensure a certain quality of approximation. We show that with high probability the KL divergence can be made arbitrarily small by growing M more slowly than N. A particular case is that for regression with normally distributed inputs in D-dimensions with the Squared Exponential kernel, M=O(logDN) suffices. Our results show that as datasets grow, Gaussian process posteriors can be approximated cheaply, and provide a concrete rule for how to increase M in continual learning scenarios
