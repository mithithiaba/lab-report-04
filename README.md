# lab-report-04
Implementation of Minimax and Alpha-Beta Pruning for Optimal Decision Making

NAME : Thiaba Rahman Methi ID : 232002042

Course Title: Artificial Intelligence Lab Course Code: CSE-316 Section:232_D7

**Problem**

You are required to implement a Python program that generates a random binary game tree with leaf node scores (for example, 8 or 16 leaf nodes). The program must apply both the Minimax algorithm and the Alpha-Beta Pruning algorithm on the same tree to determine the optimal value. It should also count and display how many nodes are evaluated in each algorithm, how many nodes are pruned in Alpha-Beta Pruning, and finally calculate the percentage improvement in efficiency achieved by Alpha-Beta Pruning compared to Minimax. No input is required, as the leaf node values will be generated randomly within the program.

**Solution**

In this problem, I used the Minimax and Alpha-Beta Pruning approach to solve the binary game tree task. The idea is to generate random leaf node values and then apply both algorithms on the same tree to find the optimal value. Minimax checks all possible nodes in the tree to make the best decision, while Alpha-Beta Pruning improves the process by avoiding the evaluation of branches that cannot affect the final result. During execution, I also counted how many nodes were evaluated in both algorithms and how many nodes were pruned in Alpha-Beta Pruning. Finally, I compared their performance by calculating the efficiency improvement of Alpha-Beta Pruning over Minimax.

**Steps**

First, generate random leaf node values to represent the terminal nodes of the binary game tree. Then calculate the depth of the tree from the total number of leaf nodes. After that, apply the Minimax algorithm to evaluate all possible nodes and determine the optimal value while counting the number of visited nodes. Next, apply the Alpha-Beta Pruning algorithm on the same tree by using alpha and beta values to skip unnecessary branches, and count both the visited nodes and pruned nodes. Finally, compare the results of both algorithms and calculate the efficiency improvement, then display all the output values.

**Case#1Output:**
Generated Leaf Nodes: [3, 5, 2, 9, 12, 5, 23, 23]
Minimax:
    Nodes Evaluated: 15
    Optimal Value: 12
Alpha-Beta Pruning:
    Nodes Evaluated: 9
    Nodes Pruned: 6
Efficiency Improvement: 40.0%

**Case#2Output:**
Generated Leaf Nodes: [8, 6, 7, 4, 15, 10, 9, 11]
Minimax:
    Nodes Evaluated: 15
    Optimal Value: 9
Alpha-Beta Pruning:
    Nodes Evaluated: 11
    Nodes Pruned: 4
Efficiency Improvement: 26.67%
