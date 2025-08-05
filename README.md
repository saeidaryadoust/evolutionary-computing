# Evolutionary Computing Exercises

This repository contains four hands-on exercises exploring key concepts in evolutionary computing, implemented in Python and MATLAB. Each assignment focuses on a different domain: discrete combinatorial problems, constrained real-valued optimization, continuous function optimization, and multi-objective trade-offs.

---

## Assignment 1: Genetic Algorithm for 8‑Queens

* **Objective:** Solve the classic 8-Queens puzzle using a simple genetic algorithm (GA).
* **Key Concepts:**

  * Solution encoding as integer vectors representing queen positions.
  * Crossover and mutation operators designed to maintain feasibility (no two queens in the same row).
  * Fitness evaluation based on the number of non-attacking pairs.
* **Implementation:** Python
* **Outcome:** Demonstrates how GA operators and selection pressure guide populations to valid chessboard configurations.

---

## Assignment 2: Road Alignment via Real‑Valued GA

* **Objective:** Optimize the alignment of a hypothetical road network using a GA with real-valued representations.
* **Key Concepts:**

  * Variable-length real-valued vectors encoding road segments.
  * Custom constraint handling for maximum curvature and construction cost.
  * Multi-criteria fitness combining route smoothness and total expense.
* **Implementation:** MATLAB
* **Outcome:** Illustrates GA on continuous search spaces with domain-specific constraints.

---

## Assignment 3: Adaptive Evolution Strategies (ES)

* **Objective:** Perform continuous optimization on benchmark functions using adaptive ES.
* **Key Concepts:**

  * Self-adaptive step-size control (sigma adaptation).
  * (1+1)-ES and (μ/ρ, λ)-ES variants.
  * Performance analysis on unimodal and multimodal landscapes.
* **Implementation:** Python
* **Outcome:** Shows how ES dynamically adjusts exploration scale to efficiently converge in varied landscapes.

---

## Assignment 4: Multi‑Objective Feature Selection

* **Objective:** Apply a multi-objective evolutionary algorithm for selecting feature subsets that balance classification accuracy against model simplicity.
* **Key Concepts:**

  * Binary encoding for feature inclusion/exclusion.
  * MOEA/D decomposition strategy.
  * Pareto front construction and visualization.
  * Quantitative metrics: hypervolume, spread, and generational distance.
* **Implementation:** MATLAB
* **Outcome:** Provides a template for tackling real-world trade-off problems using multi-objective evolutionary methods.

---
 use and adapt these exercises for educational purposes.
