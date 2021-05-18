# DAA-Practical-2021

@1: Red- Black Tree :-
  -> Complexity Analysis:
  Search:- O(log n)
  Insert:- O(log n)
  Delete:- O(log n)
  
  -> Applications:
 a) Majority of self-balancing BST library functions like map, set in cpp use Red-Black Tree.
 b) Used to implement CPU Scheduling Linux.
 c) Used in the K-mean clustering algorithm for reducing time-complexity.
 d) MySQL uses the RB tree for indexes on tables.


@2: Minimum Spanning Tree :-
  -> Complexity Analysis:
  Best Case:     O(N logE) 
  Worst Case:    O(ElogE)
  Average Case:  O(ElogE)
  
  -> Applications:
  Used to find a minimum path to connect all nodes in a graph. It's common applications are given below −
  a) Civil Network Planning
  b) Computer Network Routing Protocol
  c) Cluster Analysis
 
 
 @3: Sorting :-
 --->Bubble
    ->Complexity:
       a) Worst and Average Case Time Complexity: O(n*n). 
       b) Best Case Time Complexity: O(n).
  
    ->Application of Bubble Sort:
       a)Due to its simplicity, bubble sort is used to introduce the concept of a sorting algorithm.
       b)In computer graphics it is popular for its capability to detect a very small error (like swap of just two elements) in almost-sorted arrays.
 
 --->Selection
    ->Complexity:
       O(n^2) - 2 nested loops in cases.
 
    ->Application:
       a)Selection sort almost always outperforms bubble sort and gnome sort.
       b)Can be useful when memory write is a costly operation
      
 
 --->Insertion
    ->Complexity:
       Worst case time complexity: Θ(N^2) comparisons and swaps
       Average case time complexity: Θ(N^2) comparisons and swaps
       Best case time complexity: Θ(N) comparisons and Θ(1) swaps
  
    ->Application:
     a)If the cost of comparisons exceeds the cost of swaps, as is the case for example with string keys stored by reference or with human interaction, then using binary insertion sort may yield better performance.
     b)A variant named binary merge sort uses a binary insertion sort to sort groups of 32 elements, followed by a final sort using merge sort.

 
 --->Merge
   >Complexity:
     Worst case time complexity: Θ(N log N)
     Average case time complexity: Θ(N log N)
     Best case time complexity: Θ(N log N)
    Time complexity of Merge Sort is  θ(nLogn) in all 3 cases (worst, average and best) as merge sort always divides the array into two halves and takes linear time to merge two halves.
  
  ->Applications:
    a)Merge Sort is useful for sorting linked lists in O(n Log n) time
    b)Merge sort can be implemented without extra space for linked lists
    c)Merge sort is used in external sorting
 
 --->Quick 
   ->Complexity:
       Worst case time complexity: Θ(N^2)
       Average case time complexity: Θ(N log N)
       Best case time complexity: Θ(N log N)
 

   ->Applications:
    a)Quicksort is used everywhere where a stable sort is not needed
    b)Quick Sort is a cache friendly sorting algorithm as it has good locality of reference when used for arrays
    c)Quick Sort is an in-place sort that is does not require any extra storage
