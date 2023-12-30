## **Project 0: Guess the Number**

## Table of Contents
1. [Work Problem](README.md#work-problem)
2. [Work Stages](README.md#work-stages)
3. [Results](README.md#results)
4. [Conclusion](README.md#conclusion)


### Work Problem
To write an algorithm that guesses a computer generated number in a minimum number of attempts.

#### Conditions

Using Python's NumPy library computer generates a random integer from 1 to 100, and the user (you) needs to guess it

#### Quality Metric

Results are assessed by the average number of attempts per 1000 repetitions.

#### What do we practice?

- learning to code in Python
- learning to use VisualCode and working with GitHub
- designing a project

:arrow_up:[Table of Contents](README.md#table-of-contents)


### Work Stages
- reviewed the initial code in [*game*](https://github.com/tori938/PROJECT-0/blob/main/game_v1.py) and noted down the number of attempts made, i.e. by using the binary tree search the number of attempts can be reduced to =< 8
- reviewed the secondary code in *random_predict* that simply selects a random number from 1 to 100
- adjusted the code from *random_predict* to create *guess_the_number* algorithm that uses the binary search to find the number

:arrow_up:[Table of Contents](README.md#table-of-contents)


### Results
1. algorithm in *game* requires the user input to guess the number, i.e. number of attempts dependent on the user
2. algorithm in *random_predict* guesses the number in 101 attempts on average
3. algorithm in *guess_the_number* guesses the number in 5 attempts on average

:arrow_up:[Table of Contents](README.md#table-of-contents)


### Conclusion
By using the binary search and making slight adjustments to the source code, it was possible to reduce the average number of guessing attempts to 5.

:arrow_up:[Table of Contents](README.md#table-of-contents)
