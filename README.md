## Design and Analysis of Algorithms (DAA)

This repository contains Python implementations of algorithms covered in the Design and Analysis of Algorithms (DAA) laboratory.

The programs focus on fundamental sorting, searching, recursion, dynamic programming, and algorithm analysis concepts, including time and space complexity.

## 📚 Programs
Sorting Algorithms
Bubble Sort
Selection Sort
Insertion Sort
Merge Sort
Quick Sort
Heap Sort (Max Heap)
Searching Algorithms
Linear Search
Binary Search
Dynamic Programming
0/1 Knapsack using Dynamic Programming
Matrix Chain Multiplication using Dynamic Programming
Making Change Problem using Dynamic Programming
Other Algorithms
Factorial using Iterative Method
Factorial using Recursive Method
💻 Programming Language
Python 3
##📊 Time Complexity
Algorithm	Best Case	Average Case	Worst Case
Bubble Sort	O(n)	O(n²)	O(n²)
Selection Sort	O(n²)	O(n²)	O(n²)
Insertion Sort	O(n)	O(n²)	O(n²)
Merge Sort	O(n log n)	O(n log n)	O(n log n)
Quick Sort	O(n log n)	O(n log n)	O(n²)
Heap Sort	O(n log n)	O(n log n)	O(n log n)
Linear Search	O(1)	O(n)	O(n)
Binary Search	O(1)	O(log n)	O(log n)
0/1 Knapsack (DP)	O(nW)	O(nW)	O(nW)
Matrix Chain Multiplication (DP)	O(n³)	O(n³)	O(n³)
Making Change (DP)	O(nA)	O(nA)	O(nA)
Factorial – Iterative	O(n)	O(n)	O(n)
Factorial – Recursive	O(n)	O(n)	O(n)

Space Complexity:

0/1 Knapsack: O(nW)
Matrix Chain Multiplication: O(n²)
Making Change: O(A)
Factorial – Iterative: O(1)
Factorial – Recursive: O(n)

Where:

n = number of items, matrices, or coins
W = knapsack capacity
A = target amount
Requirements
Python 3.x
Google Colab or any Python IDE
No external libraries are required for the algorithms.
How to Run
Using Google Colab
Open Google Colab.
Upload the required .ipynb file.
Run the cells sequentially.
Enter the input when prompted.
Using Python

Clone the repository and run the required Python program:

git clone <your-repository-url>
cd <repository-name>
python filename.py
Repository Structure
DAA/
│
├── Sorting/
│   ├── bubble_sort.py
│   ├── selection_sort.py
│   ├── insertion_sort.py
│   ├── merge_sort.py
│   ├── quick_sort.py
│   └── heap_sort.py
│
├── Searching/
│   ├── linear_search.py
│   └── binary_search.py
│
├── Dynamic_Programming/
│   ├── knapsack.py
│   ├── matrix_chain_multiplication.py
│   └── making_change.py
│
├── Recursion/
│   ├── factorial_iterative.py
│   └── factorial_recursive.py
│
└── README.md
Objectives
Understand fundamental algorithms.
Implement algorithms using Python.
Analyze time and space complexity.
Compare different algorithmic approaches.
Understand Dynamic Programming concepts.
Implement 0/1 Knapsack using Dynamic Programming.
Implement Matrix Chain Multiplication using Dynamic Programming.
Implement the Making Change Problem using Dynamic Programming.
Understand optimal substructure and overlapping subproblems.
Practice algorithm implementation for DAA laboratory work.
Topics Covered
Sorting
Searching
Recursion
Dynamic Programming
0/1 Knapsack – Dynamic Programming
Matrix Chain Multiplication – Dynamic Programming
Making Change – Dynamic Programming
Divide and Conquer
Heap and Heap Sort
Time Complexity
Space Complexity
Best, Average, and Worst Case Analysis
Optimal Substructure
Overlapping Subproblems
