## Python for useRs

I decided to write this notebook to annotate my own experience in translating R to Python, as my current job is done almost entirely using the later. 

I'm a huge fan of the `tidyverse` and it's philosofy of reducing the programmer's time first and then the CPU time. So, for many things that I can acomplish in R with just a few **readable** lines of code, I had to google how to do them using `pandas` and very often the solution was an obscure piece of *hack* or simply something not that obvious.

As I imagine that this may happen to other people, I decided to share my experience with the world. So, here we go!

### Notebooks

 * [Anti join](https://github.com/toneloy/pythonforuseRs/blob/master/Anti%20join.ipynb): we have two tables, lets say `df1` and `df2` and we want to filter the records on `df1` that aren't in `df2`, using a set of variables in common.
 * [Group and mutate](https://github.com/toneloy/pythonforuseRs/blob/master/Group%20and%20mutate.ipynb): we want to make a calculation that depends on an aggregate by groups. For example, we want to standardize a variable using the mean and standard deviation by groups of another variable.