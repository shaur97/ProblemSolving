# Problem: Given an integer find if there exists a sum for a path from root to leaf in a tree. 

## Solution Explanation

#### Take the input sum and keep subtracting the value of the node at every level. if we get a zero at the leaf, sum exists else doesn't exist. Do this for all paths.