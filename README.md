# Insertion-sort
Veri algoritmaları
# Insertion Sort Project

Hello everyone , I have completed project 1 called "Insertion Sort Project" which organized by [Patika.dev](https://www.patika.dev/tr)

## Project 1

**[22,27,16,2,18,6] -> Insertion Sort**

### 1.Write the stages of the above given array according to the sort type.

#### Answer:

` | [2,27,16,22,18,6] | (n-1) |`

` | [2,6,16,22,18,27] | (n-2) |`

` | [2,6,16,18,22,27] | (n-3) |`

------------

### 2.Write the Big-O notation.

#### Answer:
`| O(n^2) |`

### 3.Write the type of Time Complexities notation.

#### Answer:

`| Average Case :  O(n^2) |`

`| Best Case : O(n) |`

`| Worst Case : O(n^2) |`

### 4.What case does the number 18 fall into after the array is sorted? Write.

#### Answer:

`| Average Case |`

### 5.Write the first 4 steps of [7,3,5,8,2,9,4,15.6] according to Insertion Sort.

#### Answer:

`| Step 1 --> [2,3,5,8,7,9,4,15,6] |`

`| Step 2 --> [2,3,4,8,7,9,5,15,6] |`

`| Step 3 --> [2,3,4,5,7,9,8,15,6] |`

`| Step 4 --> [2,3,4,5,6,9,8,15,7] |`

#### Extra:

`| Step 5 --> [2,3,4,5,6,7,8,15,9] |`

`| Step 6 --> [2,3,4,5,6,7,8,9,15] |`





# Merge Sort Project

Hello everyone , I have completed project 1 called "Insertion Sort Project" which organized by [Patika.dev](https://www.patika.dev/tr)

## Project 2

**[16,21,11,8,12,22] -> Merge Sort**

### 1.Write the stages of the above given array according to the sort type.

#### Answer:

`| Step 1 --> [16,21,11,8,12,22] |`

`| Step 2 --> [16,21,11] - [8,12,22] |`

`| Step 3 --> [16] - [21,11] -- [8,12] - [22] |`

`| Step 4 --> [16] - [21] - [11] -- [8] - [12] - [22] |`

`| Step 5 --> [16] - [11,21] -- [8,12] - [22] |`

` | Step 6 --> [11,16,21] -- [8,12,22] |`

`| Step 7 --> [8,11,12,16,21,22] |`

### 2.Write the Big-O notation.

#### Answer:

`| O(n*(logn)) |`


# Binary Search Tree Project

Hello everyone , I have completed project 1 called "Insertion Sort Project" which organized by [Patika.dev](https://www.patika.dev/tr)

## Project 3

**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] -> Binary-Search-Tree**

### 1.Write the stages of the above given array according to the sort type.

#### Answer:


**Root = 7**

	       7
	      /	 \
	     5 	  8
	    / \     \
	    1 6      9
	   / \
	  0   3
	     / \
	    2   4



######  On the left of the root : 0,1,2,3,4,5,6
######  On the right of the root : 8,9
