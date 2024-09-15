Heapsort
The heapsort.py file contains the implementation of the Heapsort algorithm. Heapsort is a comparison-based sorting algorithm that utilizes a binary heap to sort an array. It includes methods for:

Building a max-heap
Performing Heapsort
Maintaining the heap property
Usage
Import the HeapSort class from heapsort.py.
Create an instance of HeapSort with the array to be sorted.
Call the heapsort method to sort the array.
Example:

python
Copy code
from heapsort import HeapSort

data = [4, 10, 3, 5, 1]
heap_sort = HeapSort(data)
sorted_data = heap_sort.heapsort()
print(sorted_data)  # Output: [1, 3, 4, 5, 10]
Priority Queue
The priority_queue.py file contains the implementation of a priority queue using a binary heap. It supports the following operations:

Inserting tasks into the queue
Extracting the highest-priority task
Increasing the priority of a task
Checking if the queue is empty
Usage
Import the Task and PriorityQueue classes from priority_queue.py.
Create tasks with attributes such as task_id, priority, arrival_time, and deadline.
Use the PriorityQueue class to manage tasks based on priority.
