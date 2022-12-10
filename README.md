# Nonogram
 The Nonogram is a picture logic puzzle. The task is to generate an image on a grid by filling initially empty cells with unbroken lines of filled-in squares corresponding to the numbers predefined for the columns and rows. The grids are filled with black and white pixels while adhering to a description that specifies the lengths of consecutive black pixel segments for each row and column. After the successful completion, a hidden pixel-art picture is revealed. In this paper, we discussed several approaches to solve this problem, referring to topics such as tree search and local search. We will implement two approaches to solving this problem. As one approach, we defined our problem as Constraint Satisfaction Problem, and the other way we used is Genetic Algorithms to achieve a solution. Although Nonograms in puzzle books ordinarily are possible to solve by hand, however, in computational informatics, they are generally considered as NP-hard problems that usually require exponential time to find a possible solution.
## Documents
Please take a look in the docks folder, there you can find our presentation slides and our paper
## Data
We have used from this [dataset](https://raw.githubusercontent.com/susarip/test/master/hanjie_scraper/hanjie_scraper/hanjie.csv).
You can find the dataset in our data folder as well.

## Methods
Genetic Algorithm - /GA folder
<br>
Creative Genetic Algorithm - /CGA folder
<br>
Constraint Satisfactory Problem - /CSP folder
### Genetic Algorithm
Genetic Algorithm with traditional fitness
### Creative Genetic Algorithm
Genetic Algorithm with 2 subagents: Row Subagent and column Subagent.
### CSP
Defining problem with CSP and solving it with backtracking algorithm.



If you have any question you can contact us:
<br>
vahan@yeranosyanvahan.com 
<br>
liana_darbinyan@edu.aua.am 
<br>
hayk_hovhannisyan@edu.aua.am