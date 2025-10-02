# STACK-IMPLEMENTATION
# Aim:
To study and implement the concept of Stack in C++ using arrays and functions with operations such as PUSH, POP, and PEEK.
# Objectives:
- 1.To understand the concept of Stack as an Abstract Data Type.
- 2.To implement Stack operations using arrays.
- 3.To study the behavior of LIFO (Last In, First Out).
- 4.To handle Stack Overflow and Underflow conditions.
- 5.To analyze real-life applications of Stack.
# Theory:
A Stack is a linear data structure that follows the LIFO principle. In this structure, insertion (PUSH) and deletion (POP) operations are performed from only one end called the "TOP".

Key Operations:

- 1.PUSH: Insert an element into the stack.
POP: Remove the top element from the stack.
- 2.PEEK/TOP: Retrieve the top element without removing it.
isEmpty: Check if the stack is empty.
- 3.isFull: Check if the stack is full.

Applications of Stack:

- 1.Expression evaluation (postfix, prefix, infix).
- 2.Function call management in recursion.
- 3.Undo/Redo operations in text editors.
- 4.Backtracking algorithms (maze solving, DFS).
- 5.Browser history navigation.

# Algorithm (for Array-based Stack):
- 1.Initialize stack with maximum size and top = -1.
- 2.PUSH Operation:
If top == MAX-1 → Stack Overflow.
Else increment top and insert element.
- 3.POP Operation:
If top == -1 → Stack Underflow.
Else return element at top and decrement top.
- 4.PEEK Operation:
If stack not empty → return element at top.
Else → stack empty message.
- 5.Repeat as per user choice.

# Conclusion:
- Stack is a simple but powerful data structure that works on LIFO.
- It is widely used in memory management, expression evaluation, function calls, and backtracking problems.
- Implementation using arrays is simple, but has a fixed size.
- For dynamic sizing, linked list based implementation is preferred.
- Understanding Stack forms the foundation of advanced DS & Algorithms.
