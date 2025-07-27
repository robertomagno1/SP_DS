# SP\_DS — Stochastic Processes: Compound Renewal and Jump Models

🗕️ **Exam Sheet** – July 2025
📄 **Compiled PDF**: [mainDocument.pdf](https://raw.githubusercontent.com/robertomagno1/SP_DS/main/mainDocument.pdf)

---

## 📚 Description

This repository contains a written assignment on **Compound Renewal Processes** and associated jump processes, within the broader framework of **Stochastic Processes for Data Science**.

The work presents a mathematical formulation and analytical discussion of processes defined as:

* Interevent times: \$J\_i\$
* Event counting process: \$N(t)\$
* Jump sizes: \$X\_i\$
* Accumulated jumps over time: \$Z(t) = \sum\_{i=1}^{N(t)} X\_i\$

The document addresses the following theoretical aspects:

* Derivation of distribution functions (CDFs and PDFs) for \$T\_n\$, \$N(t)\$, \$Z\_n\$, and \$Z(t)\$
* Finite-dimensional distributions of \$Z(t)\$
* Existence and path properties of \$Z(t)\$
* Conditions for \$Z(t)\$ being a **Markov process**
* Conditions for \$Z(t)\$ being a **Martingale**

---

## 📁 Repository Structure

```
SP_DS/
├── README.md              # This file
├── main.tex               # LaTeX source of the exam document
├── mainDocument.pdf       # Compiled PDF of the exam sheet
└── ref/                   # Reference literature (PDFs)
    ├── KOLMOGOROV.pdf
    ├── Lecture Notes on Gaussian Processes with Examples.pdf
    ├── Predicting the future from the past-.pdf
    └── Reproducing-Kernel-Hilbert-Spaces.pdf
```

---

## 📌 Requirements

To compile the LaTeX document, you'll need:

* A LaTeX distribution (e.g., TeX Live, MiKTeX)
* Packages: `amsmath`, `amssymb`, `amsfonts`, `graphicx`

---

## 📖 References

The `ref/` folder contains supporting literature and theoretical foundations used throughout the assignment:

* **Kolmogorov's Foundations of Probability**
* *Lecture Notes on Gaussian Processes with Examples*
* *Predicting the Future from the Past*
* *Reproducing Kernel Hilbert Spaces*

Please refer to the document itself for inline citations and references.

## 📬 Contact

For questions or contributions, please contact the repository owner or open an issue.

---

🧠 *This project is part of coursework in Stochastic Processes for Data Science and aims to combine rigorous probability theory with practical modeling challenges.*
