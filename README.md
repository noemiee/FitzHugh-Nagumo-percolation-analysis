## Notebook content: 

(1) Performs integration of a system consisting of $N$ diffusively coupled stochastic FitzHugh-Nagumo oscillators on a 1D lattice with periodic boundary conditions. The time evolution of the state $(u_k,v_k)$ at node $k$ is described by

$$\epsilon \dot{u_k} = f(u_k) - v_k + I + (\Delta u)_k + \sqrt{2D^{(u)}}\eta^{(u)}_k, $$

$$\dot{v_k} = u_k - b v_k + c + (\Delta v)_k + \sqrt{2D^{(v)}}\eta^{(v)}_k$$

for $k=1,...,N$, with $f(u) = \alpha u(u-a)(1-u)$.

(2) Compute a time-dependent functional network describing the evolution of correlations in the system.

(3) Compute and analyze evolution of percolation measures (Size of the largest connected component, probability that a randomly chosen node belongs to a component of size 2) on the time-dependent network.  


