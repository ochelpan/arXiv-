# arxiv digest (quant-ph + cond-mat) — 2026-04-24

*3 papers · 1 highlighted*


## ⭐ Highlighted (1)

*Papers by authors on your watch list. They also appear in their normal category below.*

### ⭐ [Algorithmic Locality via Provable Convergence in Quantum Tensor Networks](http://arxiv.org/abs/2604.21919v1)

**Highlighted author(s):** Sarang Gopalakrishnan  
**Authors:** Siddhant Midha, Yifan F. Zhang, Daniel Malz, Dmitry A. Abanin, Sarang Gopalakrishnan  
**Type:** theory · **PDF:** <https://arxiv.org/pdf/2604.21919v1>  
**Analysis basis:** full extracted PDF text; 7 chunk(s) analyzed

**Main problem.** The paper addresses the lack of rigorous theoretical guarantees for the convergence and accuracy of Belief Propagation (BP) when used to evaluate high-dimensional tensor networks like PEPS.

**Main result.** The authors prove that for strongly injective PEPS, BP fixed points can be found efficiently and that a 'cluster-corrected' BP algorithm achieves polynomial-time computation with controlled error. They also establish 'algorithmic locality,' where local perturbations to the tensor network only affect the BP fixed point and observables with exponentially decaying influence.

**Method.** The study employs the mathematical framework of tensor networks (PEPS), utilizing cluster expansions, loop expansion techniques, and the theory of Banach contractions to analyze message-passing dynamics and the stability of injective tensors.

**Summary.** This work provides the first end-to-end theoretical framework for the convergence of Belief Propagation in a specific class of Projected Entangled Pair States (PEPS). By focusing on 'strongly injective' tensors, the authors prove that the BP algorithm is both efficient and accurate, with errors that can be controlled to polynomial scales. A key discovery is 'algorithmic locality,' which means that local changes to the system do not require a global recalculation, as the impact of the change decays exponentially with distance. This result bridges the gap between the widely used numerical practice of BP and rigorous mathematical proofs of its performance.

<details><summary>Abstract</summary>

Belief propagation has recently emerged as a powerful framework for evaluating tensor networks in higher dimensions, combining computational efficiency with provable analytical guarantees. In this work, we develop the first end-to-end theory of tensor network belief propagation for a class of projected entangled pair states satisfying \emph{strong injectivity}. We show that when the injectivity parameter exceeds a constant threshold, BP fixed points can be found efficiently, and a cluster-corrected BP algorithm computes physical quantities to $1/\mathrm{poly}(N)$ error in $\mathrm{poly}(N)$ time for an $N$ qubit system. We identify a striking phenomenon we term \emph{algorithmic locality}: local perturbations of the tensor network affect the BP fixed point with an influence decaying rapidly with distance. As a result, updates to the fixed point after a local perturbation can be carried out using only local recomputation. Moreover, through the cluster expansion, this locality extends to observables, implying that local expectation values can be approximated from local data with controlled accuracy. Our results provide the first rigorous guarantee for the effectiveness of tensor-network belief propagation on a wide class of many-body states, bridging a gap between widely used numerical practice and provable algorithmic performance.

</details>


## quantum information and computing (1)

### [Dual-use quantum hardware for quantum resource generation and energy storage](http://arxiv.org/abs/2604.21913v1)

**Authors:** Vaibhav Sharma, Yiming Wang, Shouvik Sur  
**Type:** theory · **PDF:** <https://arxiv.org/pdf/2604.21913v1>  
**Analysis basis:** abstract only; all chunk analyses failed

![main figure](2604.21913v1.png)

**Main problem.** The paper addresses the challenge of efficiently generating quantum resources (like entanglement) and the separate challenge of developing efficient quantum batteries for energy storage.

**Main result.** The authors demonstrate that quantum resource generation and quantum battery charging are dual processes that can be achieved simultaneously. They propose a hardware protocol for superconducting circuits that can switch between energy storage and quantum sensing without additional hardware cost.

**Method.** The study uses a theoretical framework to establish a connection between protocols for generating metrologically useful states and collective charging advantages in quantum batteries, specifically applied to superconducting circuit architectures.

**Summary.** This paper explores a way to make quantum hardware more versatile by linking two different tasks: creating useful quantum states for sensing and charging quantum batteries for energy storage. The researchers show that the same experimental process can be used for both purposes, providing a 'dual-use' functionality. This means a single quantum device could switch between acting as a sensor and acting as a battery. This approach allows for more efficient, modular quantum architectures that do more with less hardware.

<details><summary>Abstract</summary>

Quantum resources such as entanglement form the backbone of quantum technologies and their efficient generation is a central objective of modern quantum platforms. Independently, quantum batteries have emerged as nanoscale devices that utilize collective quantum effects to store energy with a charging advantage over classical strategies. Here, we show that these two pursuits can co-exist: protocols for fast generation of resourceful quantum states can simultaneously charge a quantum battery with a collective advantage, and conversely, a quantum battery protocol with a charging advantage can produce resource-rich states. Using this connection, we propose an integrated hardware protocol on superconducting circuits in which each experimental run can interchangeably accomplish either quantum battery charging, or quantum sensing through generation of metrologically useful states. Our results establish that quantum resources and stored energy are distinct yet co-producable quantities, opening the door to modular quantum architectures that dynamically switch between sensing and energy-storage functions, thereby producing additional functionalities without extra hardware cost.

</details>


## numerical methods (1)

### ⭐ [Algorithmic Locality via Provable Convergence in Quantum Tensor Networks](http://arxiv.org/abs/2604.21919v1)

**Highlighted author(s):** Sarang Gopalakrishnan  
**Authors:** Siddhant Midha, Yifan F. Zhang, Daniel Malz, Dmitry A. Abanin, Sarang Gopalakrishnan  
**Type:** theory · **PDF:** <https://arxiv.org/pdf/2604.21919v1>  
**Analysis basis:** full extracted PDF text; 7 chunk(s) analyzed

**Main problem.** The paper addresses the lack of rigorous theoretical guarantees for the convergence and accuracy of Belief Propagation (BP) when used to evaluate high-dimensional tensor networks like PEPS.

**Main result.** The authors prove that for strongly injective PEPS, BP fixed points can be found efficiently and that a 'cluster-corrected' BP algorithm achieves polynomial-time computation with controlled error. They also establish 'algorithmic locality,' where local perturbations to the tensor network only affect the BP fixed point and observables with exponentially decaying influence.

**Method.** The study employs the mathematical framework of tensor networks (PEPS), utilizing cluster expansions, loop expansion techniques, and the theory of Banach contractions to analyze message-passing dynamics and the stability of injective tensors.

**Summary.** This work provides the first end-to-end theoretical framework for the convergence of Belief Propagation in a specific class of Projected Entangled Pair States (PEPS). By focusing on 'strongly injective' tensors, the authors prove that the BP algorithm is both efficient and accurate, with errors that can be controlled to polynomial scales. A key discovery is 'algorithmic locality,' which means that local changes to the system do not require a global recalculation, as the impact of the change decays exponentially with distance. This result bridges the gap between the widely used numerical practice of BP and rigorous mathematical proofs of its performance.

<details><summary>Abstract</summary>

Belief propagation has recently emerged as a powerful framework for evaluating tensor networks in higher dimensions, combining computational efficiency with provable analytical guarantees. In this work, we develop the first end-to-end theory of tensor network belief propagation for a class of projected entangled pair states satisfying \emph{strong injectivity}. We show that when the injectivity parameter exceeds a constant threshold, BP fixed points can be found efficiently, and a cluster-corrected BP algorithm computes physical quantities to $1/\mathrm{poly}(N)$ error in $\mathrm{poly}(N)$ time for an $N$ qubit system. We identify a striking phenomenon we term \emph{algorithmic locality}: local perturbations of the tensor network affect the BP fixed point with an influence decaying rapidly with distance. As a result, updates to the fixed point after a local perturbation can be carried out using only local recomputation. Moreover, through the cluster expansion, this locality extends to observables, implying that local expectation values can be approximated from local data with controlled accuracy. Our results provide the first rigorous guarantee for the effectiveness of tensor-network belief propagation on a wide class of many-body states, bridging a gap between widely used numerical practice and provable algorithmic performance.

</details>


## statistical mechanics (1)

### [Subsystem-Resolved Spectral Theory for Quantum Many-Body Hamiltonians](http://arxiv.org/abs/2604.21929v1)

**Authors:** MD Nahidul Hasan Sabit  
**Type:** theory · **PDF:** <https://arxiv.org/pdf/2604.21929v1>  
**Analysis basis:** full extracted PDF text; 2 chunk(s) analyzed

**Main problem.** The paper investigates how the locality of interactions in quantum many-body Hamiltonians influences the structure, stability, and additivity of their spectra at the subsystem level.

**Main result.** The author proves that subsystem spectra are stable under local approximations and become exactly additive for disjoint, sufficiently separated subsets in finite-range models. This establishes a static analogue to the dynamical Lieb–Robinson bounds, demonstrating that interaction geometry directly shapes spectral behavior.

**Method.** The study utilizes analytical techniques from operator theory, specifically employing Hausdorff distance between spectra and perturbation estimates of self-adjoint operators, with a nearest-neighbor spin chain used as a concrete illustration.

**Summary.** This paper introduces a subsystem-based framework to study the spectral properties of quantum many-body Hamiltonians. It demonstrates that the spectra of subsystem Hamiltonians can be accurately approximated by operators supported on finite neighborhoods, with errors that decay exponentially with distance. Furthermore, the research shows that for well-separated subsystems, the total spectrum is approximately the sum of the individual subsystem spectra. These findings provide a static counterpart to the Lieb–Robinson bounds, proving that the spatial arrangement of interactions is reflected in the organization of spectral data.

<details><summary>Abstract</summary>

We study spectral properties of quantum many-body Hamiltonians through a subsystem-based framework. Given a Hamiltonian of the form $H = \sum_{X \subseteq Λ} Φ(X)$ acting on a tensor product Hilbert space, we associate to each subset $S \subseteq Λ$ a subsystem Hamiltonian $H_S$ and its spectrum $\mathcal{S}(S) = σ(H_S)$. This produces a family of spectra indexed by subsystems, allowing spectral data to be organized according to interaction structure. We show that subsystem Hamiltonians admit local approximations: $H_S$ can be approximated by operators supported on finite neighborhoods with an error bounded by $\|H_S - H_{S,r}\| \le |S| e^{-μr} \|Φ\|_μ$. As a consequence, subsystem spectra are stable under truncation in the sense that $d_H(\mathcal{S}(S), σ(H_{S,r})) \le |S| e^{-μr} \|Φ\|_μ.$ We then prove that for disjoint subsets $S_1, S_2 \subseteq Λ$, the subsystem spectrum is approximately additive: $d_H\big(\mathcal{S}(S_1 \cup S_2), \mathcal{S}(S_1) + \mathcal{S}(S_2)\big) \le (|S_1| + |S_2|) e^{-μD} \|Φ\|_μ,$ where $D = d(S_1, S_2)$. In the finite-range case, this relation becomes exact. The results show that spectral properties reflect the locality of interactions not only at the level of operators, but also at the level of spectra. The framework provides a way to study many-body systems in which interaction geometry directly shapes spectral behavior.

</details>
