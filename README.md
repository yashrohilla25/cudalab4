# cudalab4
In question 1  We have two CUDA threads doing the following:
Thread 0: Performs iterative sum of first n = 1024 integers (from 1 to 1024).
Thread 1: Performs formula-based sum of first n = 1024 integers
We get both the iterative and formula based sum 524800 as output
In question 2 we are comparing time taken by cpp file pipelining open mp which takes 790 microseconds
in other part we get output cuda merge sort as 3724 milliseconds
