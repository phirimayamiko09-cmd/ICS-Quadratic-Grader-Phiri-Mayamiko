# ICS-Quadratic-Grader

##  Description
This is a simple single-file web app built using **HTML + JavaScript**.  
It performs two main functions:
1. **Solves a quadratic equation** (ax² + bx + c = 0).
2. **Converts numeric scores (0–100)** into letter grades using the given grading scale.

---

##  How to Run
1. Download or clone this repository.
2. Open `index.html` in any modern browser.
3. The app works fully offline — no server required.

---

## Test Cases

### Quadratic Solver
| a | b | c | Discriminant | Roots / Type |
|---|---|---|---------------|---------------|
| 1 | -3 | 2 | 1 | Two real roots (1 and 2) |
| 1 | 2 | 1 | 0 | One repeated root (-1) |
| 1 | 2 | 5 | -16 | Two complex roots (-1 ± 2i) |

### Grade Converter
| Score | Expected Grade |
|--------|----------------|
| 100 | A+ |
| 85 | A+ |
| 75 | A |
| 65 | B+ |
| 60 | B |
| 55 | C+ |
| 50 | C |
| 49 | D |
| 0 | D |
