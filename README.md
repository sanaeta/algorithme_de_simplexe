## Simplex Algorithm 

 Overview

This project is a web-based implementation of the **Simplex algorithm** used to solve linear programming problems.
It allows users to input an objective function and constraints, then computes the optimal solution step-by-step with full tableau visualization.

---

##  Features

* Solve **linear programming problems (maximization)**
* Dynamic input for:

  * Objective function coefficients
  * Constraints matrix
  * Right-hand side values
* Step-by-step **Simplex iterations**
* Automatic **pivot selection**
* Visual display of each tableau
* Highlighting of **pivot elements**
* Final solution with optimal value of Z

---

##  Tech Stack

* **Frontend:** HTML, CSS, JavaScript (Vanilla)
* **Algorithm:** Custom implementation of the Simplex method

---

##  Interface

* Input section for problem definition
* Output section showing:

  * Iteration tables
  * Entering/leaving variables
  * Final optimal solution

---

##  How It Works

1. User inputs:

   * Objective function (Z)
   * Constraints matrix (A)
   * Right-hand side vector (b)
2. The system constructs the **initial simplex tableau**
3. Iteratively:

   * Selects entering variable (max coefficient)
   * Applies minimum ratio test
   * Performs pivot operations
4. Stops when optimality condition is reached

---

##  Usage

1. Clone the repository:

```bash
git clone https://github.com/sanaeta/algorithme_de_simplexe.git
```

2. Open `index.html` in your browser

3. Enter data:

```
Z: 3 5
Constraints:
2 1
1 2
b: 10 15
```

4. Click **"Solve"**

---

##  Limitations

* Currently supports **maximization problems only**
* Does not handle:

  * Degeneracy
  * Multiple optimal solutions
  * Artificial variables (Big M / Two-phase method)

---

##  Example

Maximize:

```
Z = 3x₁ + 5x₂
```

Subject to:

```
2x₁ + x₂ ≤ 10  
x₁ + 2x₂ ≤ 15  
```

---

##  Future Improvements

* Support for **minimization problems**
* Add **Big M / Two-phase method**
* Improve UI/UX (charts, better visualization)
* Export results (PDF / CSV)

---

##  Author

**Sanae Eljaafari**

---
