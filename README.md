# Vedant Puri
PhD @ CMU | Efficient transformer architectures | Scientific ML | Triton-based attention implementations

## Featured Work

### FLARE - Fast Low-Rank Attention Routing Engine
- Unified low-rank reformulation of self-attention
- O(NM) memory scaling
- Scales to 1M tokens on a single GPU
- Benchmarked on PDE, NLP, and vision tasks

[Paper](https://huggingface.co/papers/2508.12594) | [Code](https://github.com/vpuri3/FLARE.py) | [arXiv](http://arxiv.org/abs/2508.12594)

### SNF-ROM
Projection-based nonlinear reduced-order modeling with smooth neural fields for advection-dominated PDEs.

[Journal of Computational Physics paper](https://arxiv.org/abs/2405.14890) | [Code](https://github.com/vpuri3/NeuralROMs.jl)

## Research Themes
- Efficient attention and low-rank transformers
- Neural operators and PDE surrogates
- Numerical methods for ML architectures
- Scientific computing at scale

## Open Source

### FLARE
[FLARE.py](https://github.com/vpuri3/FLARE.py): Fast Low-rank Attention Routing Engine for scalable transformer attention.

### Julia Open Source Tools
- [SciMLOperators.jl](https://github.com/vpuri3/SciMLOperators.jl): operator abstractions for SciML and PDE workflows
- [LinearSolve.jl](https://github.com/vpuri3/LinearSolve.jl): linear solver interface for scientific machine learning

Also worked on Julia ecosystem repositories including [OrdinaryDiffEq.jl](https://github.com/vpuri3/OrdinaryDiffEq.jl), [NonlinearSolve.jl](https://github.com/vpuri3/NonlinearSolve.jl), [Optimization.jl](https://github.com/vpuri3/Optimization.jl), [SciMLBase.jl](https://github.com/vpuri3/SciMLBase.jl), [SciMLSensitivity.jl](https://github.com/vpuri3/SciMLSensitivity.jl), [DiffEqFlux.jl](https://github.com/vpuri3/DiffEqFlux.jl), [StochasticDiffEq.jl](https://github.com/vpuri3/StochasticDiffEq.jl), and [DiffEqBase.jl](https://github.com/vpuri3/DiffEqBase.jl).

### KolmogorovArnold.jl
[KolmogorovArnold.jl](https://github.com/vpuri3/KolmogorovArnold.jl): KAN implementation in Julia with custom gradients.

### NekTools
[NekTools](https://github.com/vpuri3/NekTools): FORTRAN 77 post-processing toolkit for NEK5000 turbulence simulations.

## Blog
Background notes and long-form writing:
- [Website work archive](https://vpuri3.github.io/work/)
- [Website thoughts archive](https://vpuri3.github.io/thoughts/)

Planned post: **How to scale attention to 1M tokens on a single GPU**.
