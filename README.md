# Psuedo-Random-Number-Gen
Implementation of the Middle-square method, inveneted by von-Neumann, with a small difference.

The idea is as followed:

You begin with a 'seed', and an empty array.

If the 'seed' is in our array, we exit the loop, and pick the last element in the array, otherwise ... 

On each iteration, we square the 'seed', and if there are an even number of digits, we add one zero at the end.

We then return the middle digit of the square, add it to the array, and repeat the process, untill our condition is met.

To get good results, the seed should be an even number of digits, and large
