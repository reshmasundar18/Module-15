# Ex. No: 15D - Build a Heap Tree Using Python

## AIM:
To write a Python program to build a heap tree using appropriate Python package and function.

---

## ALGORITHM:

1. **Start the program.**
2. Import the `heapq` module.
3. Define a function `heaptree(H)` that takes a list `H` as input.
4. Use `heapq.heapify(H)` to convert the list into a min-heap.
5. Print the created heap.
6. **End the program.**

---

## PROGRAM:
```
import heapq
def heaptree(H):
    heapq.heapify(H)
    print("The created Heap is",H)
```

## OUTPUT:
<img width="1123" height="163" alt="image" src="https://github.com/user-attachments/assets/a8f484f4-7681-4f43-90c1-865a265fb0dd" />


## RESULT:
Thus the Python program to build a heap tree using appropriate Python package and function was written and executed successfully.
