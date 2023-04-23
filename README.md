# Algorithms-Data_Structures

<h1>Algorithms</h1>

1) Bubble Sort - Bubble sort is a simple sorting algorithm that works by repeatedly swapping adjacent elements if they are in the wrong order. It is called bubble sort because the smaller elements "bubble" to the top of the list, while the larger elements "sink" to the bottom. The algorithm proceeds by iterating through the list of elements, comparing each pair of adjacent elements, and swapping them if they are in the wrong order. This process is repeated until no more swaps are necessary, indicating that the list is sorted. Although bubble sort is simple to understand and implement, it has a worst-case time complexity of O(n^2), making it relatively inefficient for large lists. For this reason, it is usually only used for small lists or as an educational example of a sorting algorithm.

2) Insertion Sort - Insertion sort is a simple sorting algorithm that works by repeatedly taking an unsorted element and inserting it into the correct position in a sorted sub-list. It is particularly efficient for small data sets and nearly sorted lists. The algorithm proceeds by starting with a single element (the first element) and iterating through the list, comparing each subsequent element with the elements in the sorted sub-list and inserting it into the correct position. The sorted sub-list grows with each iteration until all elements have been inserted and the list is fully sorted. Insertion sort has an average and worst-case time complexity of O(n^2), making it relatively inefficient for large data sets. However, it has the advantage of being simple to understand and implement, and it performs well on small or nearly sorted lists. Additionally, insertion sort is often used as part of more complex sorting algorithms, such as merge sort or quicksort.

3) Merge Sort - Merge sort is a divide-and-conquer sorting algorithm that works by recursively dividing the input list into two halves, sorting each half, and then merging the sorted halves back together. It is a stable, comparison-based sorting algorithm with a worst-case time complexity of O(n log n). The algorithm proceeds by dividing the input list into two halves, recursively sorting each half, and then merging the sorted halves back together. The merging process involves comparing the first elements of each sorted sub-list and appending the smaller one to the output list. This process continues until one of the sub-lists is empty, at which point the remaining elements in the other sub-list are appended to the output list. Merge sort has the advantage of being a stable sorting algorithm, which means that elements with the same value retain their original order in the sorted list. Additionally, merge sort is well-suited to sorting linked lists, as it only requires changing pointers to merge the sub-lists, rather than copying elements as in an array-based implementation. However, merge sort does require additional memory for the merging process, and its recursive nature can lead to stack overflow on very large lists.

4) Quick Sort - Quick sort is a divide-and-conquer sorting algorithm that works by partitioning an input list into two sub-lists, sorting each sub-list independently, and then combining the sorted sub-lists back together. It is a highly efficient sorting algorithm, with an average time complexity of O(n log n) and a worst-case time complexity of O(n^2). The algorithm proceeds by selecting a pivot element from the input list and partitioning the list into two sub-lists, one containing elements smaller than the pivot and one containing elements larger than the pivot. The pivot element is then moved to its final position in the sorted list, and the two sub-lists are recursively sorted using the same process. Quick sort has the advantage of being an in-place sorting algorithm, meaning that it can sort the input list without requiring additional memory beyond the list itself. Additionally, quick sort is often faster than other comparison-based sorting algorithms for large data sets, due to its efficient partitioning scheme. However, quick sort can have poor performance on nearly sorted or already sorted lists, and its worst-case time complexity can be problematic for certain types of input. Various modifications to the basic algorithm, such as randomized pivot selection or hybridization with insertion sort, can mitigate these issues.

5) Selection Sort - Selection sort is a simple sorting algorithm that works by repeatedly finding the smallest element in an unsorted portion of the input list and swapping it with the first unsorted element. It has a worst-case time complexity of O(n^2), making it relatively inefficient for large data sets. The algorithm proceeds by iterating through the input list and selecting the smallest element in the unsorted portion of the list. This element is then swapped with the first unsorted element, effectively adding it to the sorted portion of the list. This process continues until the entire list is sorted. Selection sort has the advantage of being simple to implement and requiring only a small amount of additional memory for swapping elements. However, its time complexity makes it unsuitable for large data sets or real-time applications. Additionally, selection sort is not a stable sorting algorithm, meaning that the relative order of equal elements may change in the sorted list.


<h1>Data Structures</h1>

1) Binary Search Tree - A binary search tree (BST) is a data structure that organizes elements in a tree-like structure, where each node has at most two children and each node's left subtree contains only elements less than the node's value, while the right subtree contains only elements greater than the node's value. This property allows for efficient search, insertion, and deletion of elements. The structure of a BST is such that the root node represents the median element of the entire tree, with all elements less than the root node in the left subtree and all elements greater in the right subtree. This property is maintained for all nodes in the tree, making it possible to efficiently search for an element by recursively traversing the left or right subtrees based on the element's value. BSTs have several advantages over other data structures for searching and sorting, including a worst-case time complexity of O(log n) for search, insertion, and deletion operations (assuming a balanced tree), and the ability to maintain a sorted list of elements in a dynamic data structure. However, if the tree is unbalanced, the worst-case time complexity can be as bad as O(n), making it important to balance the tree periodically to maintain efficiency. Additionally, some operations, such as finding the minimum or maximum element, can be slower than in other data structures such as heaps.

2) Double Linked List - A doubly linked list is a data structure that consists of a sequence of elements, each of which contains a value and pointers to both the previous and next elements in the list. This allows for efficient traversal of the list in both directions, as well as insertion and deletion of elements at any position in the list. The structure of a doubly linked list is such that each element contains a reference to the previous and next elements in the list. This allows for efficient traversal of the list in either direction by following the appropriate pointers. Additionally, inserting or deleting an element in the middle of the list only requires updating the pointers of the adjacent elements, rather than the entire list. Doubly linked lists have several advantages over other data structures, including the ability to efficiently insert or delete elements at any position in the list and the ability to efficiently traverse the list in both directions. However, they require additional memory to store the extra pointers, and the pointers themselves can be a source of bugs if not properly managed. Additionally, doubly linked lists may not be as efficient as other data structures, such as arrays or singly linked lists, for certain operations such as indexing or sequential traversal.

3) Graph - A graph is a data structure that represents a set of objects, called vertices or nodes, and the connections between them, called edges. Graphs can be used to model a wide range of relationships, from social networks to physical systems, and are a fundamental tool in computer science and other fields. In a graph, vertices are typically represented as points or circles, and edges are represented as lines or arrows connecting pairs of vertices. The edges can be directed or undirected, meaning that they either point in a specific direction or allow for movement in either direction. The connections between vertices can also be weighted, meaning that each edge has a numerical value that represents a cost, distance, or other attribute.<br>
Graphs can be classified according to their structure and properties. Some common types of graphs include:
a) Directed graphs (digraphs), where edges have a direction
b) Undirected graphs, where edges do not have a direction
c) Weighted graphs, where edges have a numerical weight
d) Bipartite graphs, where vertices can be divided into two disjoint sets, with edges only connecting vertices from different sets
e) Complete graphs, where every pair of vertices is connected by an edge
f) Sparse graphs, where only a small fraction of possible edges are present
g) Dense graphs, where a large fraction of possible edges are present<br>
Graphs are a powerful tool for modeling complex systems and can be used for a variety of applications, such as route planning, social network analysis, and data visualization. However, the complexity of graph algorithms can make them computationally expensive for very large graphs, and the interpretation of graph structures and properties can be challenging.





