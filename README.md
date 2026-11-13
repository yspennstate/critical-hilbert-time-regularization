# Time regularization at p = 2 for critical stochastic evolution equations in Hilbert spaces

Yitzchak Shmalo

The paper (`main.tex`, `main.pdf`) treats Problem 6 of A. Agresti and M. Veraar, *Nonlinear SPDEs and maximal regularity: an extended survey*, NoDEA 32 (2025), article 123 (arXiv:2501.18561): does the regularization result of Theorem 5.7 of the survey extend to p = 2 in the critical case, where equality holds in condition (6.1) for some j?

Let X_0 be a Hilbert space, and consider the semilinear equation

    du + A u dt = F(u) dt + (B u + G(u)) dW

on the Hilbert couple (X_0, X_1), with endpoint trace space E = [X_0, X_1]_{1/2}. Assume the endpoint local well-posedness hypotheses at (p, kappa) = (2, 0), condition (6.1) for every j with equality allowed, and unweighted linear stochastic maximal regularity of (A, B) for an unbounded sequence of exponents q > 2. Then the maximal energy solution (u, sigma) has, on (0, sigma), all of the local regularity in Theorem 5.7 of the survey: almost surely, u lies in H^{theta,r}_loc((0, sigma); X_{1-theta}) for all 0 <= theta < 1/2 and 2 <= r < infinity, and in C^{theta-eps}_loc((0, sigma); X_{1-theta}) for all 0 < eps < theta < 1/2. The growth bound (5.21) of the survey is not needed.

The proof combines the critical smallness of the nonlinearities on small trace-space balls around a fixed domain vector, with a radius independent of that vector's domain norm, global continuation of higher-exponent cutoff equations on a fixed horizon, and a countable covering by deterministic restart times.

The result is local in time on (0, sigma). It gives nothing at time zero, no moment bounds for the original solution, and does not reach the temporal endpoint theta = 1/2. The higher-exponent linear maximal regularity is a hypothesis, the same one Theorem 5.7 of the survey makes.

The paper is part of the Math Brain project: https://github.com/yspennstate/math-brain-public

## Files

- `main.tex`: LaTeX source (amsart)
- `main.pdf`: compiled paper, 10 pages
