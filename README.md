# Variational Monte Carlo for Quantum Systems

This project implements a Variational Monte Carlo (VMC) framework to estimate ground-state energies of quantum systems using stochastic sampling and the variational principle.

## Systems Studied
- 1D Harmonic Oscillator
- Hydrogen Atom (1s state)

## Theory Overview
The variational principle guarantees:
E[ψ] ≥ E₀

Parameterized trial wavefunctions are optimized by minimizing the expectation value of the Hamiltonian using Monte Carlo integration.

## Methodology
- Trial wavefunctions with variational parameter α
- Local energy formalism
- Metropolis–Hastings sampling of |ψ|²
- Burn-in for equilibration
- Energy minimization over α

## Results
- Harmonic Oscillator ground state energy ≈ 0.5
- Hydrogen 1s ground state energy ≈ −0.5
- Results match analytical solutions

## Installation
```bash
pip install -r requirements.txt

