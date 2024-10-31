# Riemann-Wirtinger Integrals via Intersection Theory

This repository contains Mathematica notebooks for calculating Riemann-Wirtinger (RW) integrals through intersection theory methods, including symbolic and numerical approaches. Each module targets specific aspects of RW integral calculations, such as divergent integrals, initial values, asymptotic behaviors, and monodromy relations.

## Overview of Modules

The repository is organized into the following modules:

1. **Complex RW for Divergent RW**: Handles calculations for RW integrals that exhibit divergence, using regularization techniques.
2. **Complex RW for Divergent RW - Initial Values**: Computes initial values needed for evaluating divergent RW integrals.
3. **Asymptotic Values for RW-Integrals**: Provides asymptotic expansions to approximate RW integrals in limiting cases.
4. **Numerical RW Integrals with Pochhammer**: Numerically evaluates RW integrals using Pochhammer symbols.
5. **Leading Monodromy Relations**: Investigates monodromy relations, revealing symmetry properties among RW integrals.

Each module is self-contained, with functions that facilitate symbolic manipulation and numerical evaluation, making this repository suitable for research in mathematical physics and complex geometry.

---

## Module Details

### 1. Complex RW for Divergent RW

This module evaluates RW integrals that are divergent by default, using complex analytic techniques to handle and regularize such integrals.

- **Functions**:
  - `EvaluateDivergentIntegral`: Evaluates RW integrals for cases with expected divergence.
  - `RegularizeIntegral`: Applies regularization techniques to divergent integrals.

- **Example Usage**:
  ```mathematica
  RegularizeIntegral[integral, method]
### 2. Complex RW for Divergent RW - Initial Values

This module calculates initial values necessary for divergent RW integrals, serving as starting points for further regularization.

- **Functions**:
  - `SetInitialValues`: Sets initial values for divergent integrals.
  - `GetStartingParameters`: Retrieves starting parameters needed for calculation.

- **Example Usage**:
  ```mathematica
  SetInitialValues[parameters]
  
### 3. Asymptotic Values for RW-Integrals

Provides asymptotic expansions for RW integrals, useful for obtaining approximations where exact evaluation is challenging.

- **Functions**:
  - `AsymptoticExpansion`: Computes asymptotic expansion for RW integrals.
  - `ApproximateIntegral`: Approximates integral values based on asymptotic behavior.

- **Example Usage**:
  ```mathematica
  AsymptoticExpansion[integral, limit]

### 4. Numerical RW Integrals with Pochhammer

This module uses Pochhammer symbols to numerically evaluate RW integrals, particularly when symbolic methods fall short.

- **Functions**:
  - `NumericalRWIntegral`: Numerically evaluates RW integrals.
  - `ApplyPochhammer`: Utilizes Pochhammer symbols for improved convergence in numerical evaluations.

- **Example Usage**:
  ```mathematica
  NumericalRWIntegral[integral, params]
### 5. Leading Monodromy Relations

Explores the leading monodromy relations for RW integrals, helping to analyze symmetry and interrelation among complex cycles.

- **Functions**:
  - `CalculateMonodromyRelation`: Calculates leading monodromy relations.
  - `AnalyzeSymmetry`: Analyzes symmetry properties within RW integrals.

- **Example Usage**:
  ```mathematica
  CalculateMonodromyRelation[cycle1, cycle2]

## Purpose

The code is designed to calculate Riemann-Wirtinger integrals with a focus on intersection theory, enabling researchers to:
1. Calculate intersection numbers.
2. Symbolically evaluate integrals in the context of complex variables and cycles.
3. Use numerical integration methods where symbolic solutions are not feasible.

## Background

The Riemann-Wirtinger integrals arise in the study of periods and intersection theory within complex geometry. This code is particularly useful for:
- **Mathematical Physics**: For evaluating integrals over complex cycles and their intersection properties in scattering amplitude computations and string theory.
- **Number Theory and Algebraic Geometry**: For computations involving differential forms on complex manifolds and their period integrals.

The mathematical foundation of the code rests on the theory of differential forms, intersection numbers, and contour integration in complex spaces.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/rishabhtyagi989/Riemman-Wirtinger-Integrals-via-Intersection-theory.git
