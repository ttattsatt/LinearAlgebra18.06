# MIT 18.06: Linear Algebra (Gilbert Strang) — Self-Study

## Intent

Self-study of MIT's 18.06 (Gilbert Strang), done independently as the mathematical foundation underneath the CV/ML/LLM work in the [CS231n](#) and [CS336](#) repos. Goal is to be properly fluent in the linear algebra that shows up constantly in deep learning — matrix decompositions, eigenvalues, vector spaces — at a derivation level, not just "I can call `torch.linalg`."

Base material is [juanklopper's MIT_OCW_Linear_Algebra_18_06](https://github.com/juanklopper/MIT_OCW_Linear_Algebra_18_06) notebooks, imported and worked through/extended here.

## Course resources

- MIT OCW 18.06: [ocw.mit.edu/courses/18-06-linear-algebra-spring-2010](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)
- Lecture videos (Strang): [MIT OCW YouTube playlist](https://www.youtube.com/playlist?list=PL49CF3715CB9EF31D)
- Strang's textbook: *Introduction to Linear Algebra*
- Base notebooks: [juanklopper/MIT_OCW_Linear_Algebra_18_06](https://github.com/juanklopper/MIT_OCW_Linear_Algebra_18_06)

## Repo structure

```
LinearAlgebra18.06/
├── notebooks/              (imported + worked notebooks, by lecture)
│   ├── 01_Getting_started.ipynb
│   ├── 02_Fun_with_algebra.ipynb
│   ├── 03_Introduction_to_matrices.ipynb
│   └── ...
├── notes/                  (derivations, proofs, connections to ML)
└── README.md
```

## Progress tracker

| Lecture | Topic | Status |
|---|---|---|
| 1 | The geometry of linear equations | ⬜ Not started |
| 2 | Elimination with matrices | ⬜ Not started |
| 3 | Multiplication and inverse matrices | ⬜ Not started |
| 4 | Factorization into A = LU | ⬜ Not started |
| 5 | Transposes, permutations, vector spaces | ⬜ Not started |
| 6 | Column space and nullspace | ⬜ Not started |
| 7 | Solving Ax = 0: pivot variables, special solutions | ⬜ Not started |
| 8 | Solving Ax = b: row reduced form R | ⬜ Not started |
| 9 | Independence, basis, and dimension | ⬜ Not started |
| 10 | The four fundamental subspaces | ⬜ Not started |
| 11 | Matrix spaces, rank 1, small world graphs | ⬜ Not started |
| 12 | Graphs, networks, incidence matrices | ⬜ Not started |
| 13 | Quiz 1 review | ⬜ Not started |
| 14 | Orthogonal vectors and subspaces | ⬜ Not started |
| 15 | Projections onto subspaces | ⬜ Not started |
| 16 | Projection matrices and least squares | ⬜ Not started |
| 17 | Orthogonal matrices and Gram-Schmidt | ⬜ Not started |
| 18 | Properties of determinants | ⬜ Not started |
| 19 | Determinant formulas and cofactors | ⬜ Not started |
| 20 | Cramer's rule, inverse matrix, volume | ⬜ Not started |
| 21 | Eigenvalues and eigenvectors | ⬜ Not started |
| 22 | Diagonalization and powers of A | ⬜ Not started |
| 23 | Differential equations and exp(At) | ⬜ Not started |
| 24 | Markov matrices, Fourier series | ⬜ Not started |
| 25 | Symmetric matrices and positive definiteness | ⬜ Not started |
| 26 | Complex matrices, fast Fourier transform | ⬜ Not started |
| 27 | Positive definite matrices and minima | ⬜ Not started |
| 28 | Similar matrices and Jordan form | ⬜ Not started |
| 29 | Singular value decomposition (SVD) | ⬜ Not started |
| 30 | Linear transformations and their matrices | ⬜ Not started |
| 31 | Change of basis; image compression | ⬜ Not started |
| 32 | Quiz 2 review / Final review | ⬜ Not started |

> Status legend: ✅ Done · 🔄 In progress · ⬜ Not started
> Lecture numbering follows the standard 18.06 OCW sequence — will reconcile against the imported notebook numbering once mapped.

## Notes on scope

- This repo tracks lecture-by-lecture progress through Strang's course, not a separate problem-set/exam structure — exams are noted inline as "Quiz 1 / Quiz 2 / Final" per the OCW structure.
- Connections to ML/DL (e.g. SVD → dimensionality reduction, eigenvalues → PCA, positive definite matrices → optimization) are noted in `notes/` where they arise, but kept brief — deep dives on those applications live in CS231n/CS336.