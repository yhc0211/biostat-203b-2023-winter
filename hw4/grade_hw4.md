*Yung-Han Chang*

### Overall Grade: 110/140

### Quality of report: 10/10

- Is the homework submitted (git tag time) before deadline? 

- Is the final report in a human readable format html? 

- Is the report prepared as a dynamic document (Quarto or R markdown) for better reproducibility?

- Is the report clear (whole sentences, typos, grammar)? Do readers have a clear idea what's going on and how are results produced by just reading the report? 

    All yes

### Completeness, correctness and efficiency of solution: 75/90

- Preparation (10/20)

    Your `thirty_day_mort` is no longer binary due to scaling before changing it as factor. Thus, the results (AUC and accuracy) are different from others'. `-10`

- #1 approach (20/20)
    
- #2 approach (20/20)
    
- #3 approach (20/20)

- Comparison (5/10): No explanation. `-5`

	    
### Usage of Git: 10/10

- Are branches (`master` and `develop`) correctly set up? Is the hw submission put into the `master` branch?

- Are there enough commits? Are commit messages clear? 
          
- Is the hw3 submission tagged? 

- Are the folders (`hw1`, `hw2`, ...) created correctly? 
  
- Do not put a lot auxiliary files into version control. If any unnecessary files are in Git, take 5 points off.

    All yes

### Reproducibility: 5/10

This HW might be difficult to check reproducibility, esp for Windows users. Don't need to render each student's qmd. Just check html and let them know any practices that are not reproducible. 

- Are the materials (files and instructions) submitted to the `master` branch sufficient for reproducing all the results? Just click the `Render` button will produce the final `html` on teaching server? 

    We do not have your local path. `-5.0`

- If necessary, are there clear instructions, either in report or in a separate file, how to reproduce the results?

### R code style: 10/20

Each violation takes 2 points off, until all 20 points are depleted. The same violation in the same chunk basically does not count.

- [Rule 2.5](https://style.tidyverse.org/syntax.html#long-lines) The maximum line length is 80 characters.  

- [Rule 2.4.1](https://style.tidyverse.org/syntax.html#indenting) When indenting your code, use two spaces.  

- [Rule 2.2.4](https://style.tidyverse.org/syntax.html#infix-operators) Place spaces around all infix operators (=, +, -, &lt;-, etc.).  

    Lines 83 (111, 137), 91 (120, 145), 93 (122, 147). `-6.0`

- [Rule 2.2.1.](https://style.tidyverse.org/syntax.html#commas) Do not place a space before a comma, but always place one after a comma.

    Lines 49, 97 (98, 125, 151, etc.). `-4.0`

- [Rule 2.2.2](https://style.tidyverse.org/syntax.html#parentheses) Do not place spaces around code in parentheses or square brackets. Place a space before left parenthesis, except in a function call.
