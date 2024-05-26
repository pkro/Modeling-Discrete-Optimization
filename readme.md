## Week 1

### Intro
- Filling a knapsack is an optimization problem
- optimization is one of the most difficult problems in CS
- supply chains, scheduling, logistics...

### NP completeness
- complexity class for decision problems, e.g. can I fill a knapsack for a value above K?  /* GPT: explain */
- Informally, NP-complete problems have two properties
  - we can check a solution quickly. i.e., in polynomial time /* GPT: explain polynomial time */
  - if we can solve one NP-complete quickly, we can solve them all
- widely believed to take exponential time in the worst case

### Examples
- logistics (container shipping), energy (-transmission), sport scheduling

### Exponential runtime

- What optimization is trying is to push the point of exponential growth back so real problems can be solved.
- Example: If a solving algorithm starts to become exponential at scheduling of 100 trucks but we need more, we try to push it so it becomes exponential at 200 trucks so practical problems can be solved

### Tricks of the trade

- we lower our standards ("good enough solution")

### Optimization is important
- kidney exchange (match kidneys to patients across thousands of donnors and patients)
- disaster management (scheduling repair crews to repair grid and minimize blackout after disaster)
