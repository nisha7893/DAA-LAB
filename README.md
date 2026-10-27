<div align="center">

# MODY UNIVERSITY OF SCIENCE AND TECHNOLOGY

## School of Engineering and Technology

<br>

<img width="154" height="157" alt="Mody_University_logo" src="https://github.com/user-attachments/assets/11e32514-7869-4f2d-afc9-b45171b58488" />


<br>

# PYTHON PROGRAMMING LAB

### LAB RECORD

<br><br>

**Student Name:** NISHA
**Enrollment Number:** 240072

<br>

**Faculty Name:** Dr. P. K. Bishnoi

<br><br>

**Mody University of Science and Technology**
**School of Engineering and Technology**
Lakshmangarh, Rajasthan

</div>

---

<div style="page-break-after: always;"></div>

# INDEX

# INDEX

<table style="width:100%; border-collapse:collapse;">
  <tr>
    <th style="width:10%;">S. No.</th>
    <th style="width:65%;">Program</th>
    <th style="width:25%;">Link</th>
  </tr>

  <tr>
    <td>1</td>
    <td>Addition of Two Numbers</td>
    <td><a href="#program-1-addition-of-two-numbers">Program 1</a></td>
  </tr>

  <tr>
    <td>2</td>
    <td>Largest of Three Numbers</td>
    <td><a href="#program-2-largest-of-three-numbers">Program 2</a></td>
  </tr>

  <tr>
    <td>3</td>
    <td>Factorial of a Number</td>
    <td><a href="#program-3-factorial-of-a-number">Program 3</a></td>
  </tr>

  <tr>
    <td>4</td>
    <td>Prime Number Check</td>
    <td><a href="#program-4-prime-number-check">Program 4</a></td>
  </tr>

  <tr>
    <td>5</td>
    <td>Fibonacci Series</td>
    <td><a href="#program-5-fibonacci-series">Program 5</a></td>
  </tr>
  <tr>
    <td>6</td>
    <td>bubble sort</td>
    <td><a href="#program-6-bubble-sort">Program 6</a></td>
  </tr>
  <tr>
    <td>7</td>
    <td>selection sort</td>
    <td><a href="#program-7-selection-sort">Program 7</a></td>
  </tr>
  <tr>
    <td>8</td>
    <td>insertion sort</td>
    <td><a href="#program-7-insertion-sort">Program 8</a></td>
  </tr>
  <tr>
    <td>9</td>
    <td> Number is positive,negative or zero</td>
    <td><a href="#program-9-Number-is-positive,negative-or-zero">Program 9</a></td>
  </tr>
  <tr>
    <td>10</td>
    <td>Day of the week</td>
    <td><a href="#program-10-day-of-the-week">Program 10</a></td>
  </tr>
  <tr>
    <td>11</td>
    <td>Simple Calculator</td>
    <td><a href="#program-11-Simple-Calculator">Program 11</a></td>
  </tr>
  <tr>
    <td>12</td>
    <td>Undirected Graph</td>
    <td><a href="#program-12-Undirected-Graph">Program 12</a></td>
  </tr>
  <tr>
    <td>13</td>
    <td>Directed Graph</td>
    <td><a href="#program-13-Directed-Graph">Program 13</a></td>
  </tr>
  <tr>
    <td>14</td>
    <td>Undirected Weighted Graph</td>
    <td><a href="#program-14-Undirected-weighted-Graph">Program 14</a></td>
  </tr>
  <tr>
    <td>15</td>
    <td>Directed Weighted Graph</td>
    <td><a href="#program-15-Directed-Weighted-Graph">Program 15</a></td>
  </tr>
   <tr>
    <td>16</td>
    <td>DFS</td>
    <td><a href="#program-16-DFS">Program 16</a></td>
  </tr>
   <tr>
    <td>17</td>
    <td>BFS</td>
    <td><a href="#program-17-BFS">Program 17</a></td>
  </tr>
</table>


---

<div style="page-break-after: always;"></div>

# Program 1: Addition of Two Numbers

## Aim

To write a Python program to find the sum of two numbers.

## Program

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

sum = a + b

print("Sum =", sum)
```

## Sample Output

```text
Enter first number: 10
Enter second number: 20
Sum = 30
```
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5bd74bc0-ddb4-4295-87d6-dc97accbae54" />



[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 2: Largest of Three Numbers

## Aim

To write a Python program to find the largest among three numbers.

## Program

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a >= b and a >= c:
    largest = a
elif b >= a and b >= c:
    largest = b
else:
    largest = c

print("Largest number =", largest)
```

## Sample Output
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/76edd186-3641-4ca2-96e9-bf904450f876" />


```text
Enter first number: 10
Enter second number: 25
Enter third number: 15
Largest number = 25
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 3: Factorial of a Number

## Aim

To write a Python program to calculate the factorial of a given number.

## Program

```python
n = int(input("Enter a number: "))

fact = 1

for i in range(1, n + 1):
    fact = fact * i

print("Factorial =", fact)
```

## Sample Output
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/935b32d6-b197-4885-bf3d-6b5d3fe71320" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/760e4edf-a007-4985-829a-86b0ba3c51d5" />



```text
Enter a number: 5
Factorial = 120
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 4: Prime Number Check

## Aim

To write a Python program to check whether a given number is prime or not.

## Program

```python
n = int(input("Enter a number: "))

prime = True

if n < 2:
    prime = False
else:
    for i in range(2, n):
        if n % i == 0:
            prime = False
            break

if prime:
    print(n, "is a Prime Number")
else:
    print(n, "is not a Prime Number")
```

## Sample Output

```text
Enter a number: 7
7 is a Prime Number
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 5: Fibonacci Series

## Aim

To write a Python program to generate the Fibonacci series.

## Program

```python
n = int(input("Enter number of terms: "))

a = 0
b = 1

for i in range(n):
    print(a, end=" ")
    a, b = b, a + b
```

## Sample Output

```text
Enter number of terms: 7
0 1 1 2 3 5 8
```


[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 6: Bubble sort 

## Aim

To write a Python program to sort numbers from bubble sort.

## Program

```python
import time

start=time.time()

def bubble_sort(arr):
    n = len(arr)

    for i in range(n):
        for j in range(0, n - i - 1):
            if arr[j] > arr[j + 1]:
                arr[j], arr[j + 1] = arr[j + 1], arr[j]

    return arr


print(bubble_sort([5, 2, 8, 1, 3]))
end=time.time()
print("execution time" , end-start)
```

## Sample Output

<img width="1548" height="446" alt="image" src="https://github.com/user-attachments/assets/efd4bc1a-f107-4b20-a3ec-5d911086bfc8" />


---

<div style="page-break-after: always;"></div>

# Program 7: selection sort 

## Aim

To write a Python program to sort numbers from selection sort.

## Program

```python
import time

start=time.time()

arr = [5, 3, 8, 4, 2]

for i in range(len(arr)):
    min_index = i
    for j in range(i + 1, len(arr)):
        if arr[j] < arr[min_index]:
            min_index = j

    arr[i], arr[min_index] = arr[min_index], arr[i]

print(arr)

end=time.time()
print("execution time" , end-start)

```

## Sample Output



<img width="1702" height="546" alt="image" src="https://github.com/user-attachments/assets/50d12352-d9e4-43a8-ab4d-41d053a47b33" />
---

<div style="page-break-after: always;"></div>

# Program 7: insertion sort 

## Aim

To write a Python program to sort numbers from insertion sort.

## Program

```python
import time

start=time.time()

arr = [5, 3, 8, 4, 2]

for i in range(1, len(arr)):
    key = arr[i]
    j = i - 1

    while j >= 0 and arr[j] > key:
        arr[j + 1] = arr[j]
        j -= 1

    arr[j + 1] = key

print(arr)


end=time.time()
print("execution time" , end-start)
```

## Sample Output


<img width="1683" height="1008" alt="image" src="https://github.com/user-attachments/assets/1fa325a6-9916-4e29-9b67-3d59cb22ca95" />



<div style="page-break-after: always;"></div>

# Program 9: Number is positive,negative or zero

## Aim

To check whether a number is positive, negative, or zero

## Program

```python
n = int(input("Enter a number: "))

if n > 0:
    print("Positive")
elif n < 0:
    print("Negative")
else:
    print("Zero")
```
```text
Enter a number: 5
Factorial = 120
```

## Sample Output

<img width="766" height="545" alt="image" src="https://github.com/user-attachments/assets/4f21acea-455b-4c58-89c7-0b05823f5592" />

[Back to Index](#index)

---


<div style="page-break-after: always;"></div>

# Program 10: day of the week

## Aim
Write a program to input a number from 1 to 7 and display the corresponding day of the week.

## Program

```python
day = int(input("Enter a number (1-7): "))

if day == 1:
    print("Monday")
elif day == 2:
    print("Tuesday")
elif day == 3:
    print("Wednesday")
elif day == 4:
    print("Thursday")
elif day == 5:
    print("Friday")
elif day == 6:
    print("Saturday")
elif day == 7:
    print("Sunday")
else:
    print("Invalid input")

```

## Sample Output
````text
Enter a number (1-7): 3
Wednesday
````
<img width="1025" height="634" alt="image" src="https://github.com/user-attachments/assets/0e7372dc-903a-4d62-9442-c2d8b6e7d239" />


---

<div style="page-break-after: always;"></div>

[Back to Index](#index)

# Program 11: Simple Calculator

## Aim
To write a Python program to perform basic arithmetic operations such as addition, subtraction, multiplication, and division using conditional statements.


## Program

```python
a = float(input("Enter first number: "))
b = float(input("Enter second number: "))

print("1. Addition")
print("2. Subtraction")
print("3. Multiplication")
print("4. Division")

op = int(input("Choose operation (1-4): "))

if op == 1:
    print("Sum =", a + b)
elif op == 2:
    print("Difference =", a - b)
elif op == 3:
    print("Product =", a * b)
elif op == 4:
    if b != 0:
        print("Division =", a / b)
    else:
        print("Cannot divide by zero")
else:
    print("Invalid operation")

```

## Sample Output
````text
Enter first number: 10
Enter second number: 5
1. Addition
2. Subtraction
3. Multiplication
4. Division
Choose operation (1-4): 1
Sum = 15.0

````
<img width="834" height="612" alt="image" src="https://github.com/user-attachments/assets/4d1e88b9-a10e-4751-bcc1-43db71992bab" />


---

<div style="page-break-after: always;"></div>

[Back to Index](#index)

# Program 12: Undirected Graph

## Aim
To write a Python program to implement Undirected Graph.


## Program

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.neighbors = []


class Graph:
    def __init__(self):
        self.nodes = []

    def add_node(self, data):
        node = Node(data)
        self.nodes.append(node)
        return node

    def add_edge(self, node1, node2):
        node1.neighbors.append(node2)
        node2.neighbors.append(node1)

    def print_graph(self):
        for node in self.nodes:
            print(node.data, "->", end=" ")
            for neighbor in node.neighbors:
                print(neighbor.data, end=" ")
            print()


graph = Graph()

A = graph.add_node("A")
B = graph.add_node("B")
C = graph.add_node("C")
D = graph.add_node("D")

graph.add_edge(A, B)
graph.add_edge(A, C)
graph.add_edge(B, D)
graph.add_edge(C, D)

graph.print_graph()

```

## Sample Output

<img width="162" height="111" alt="image" src="https://github.com/user-attachments/assets/aa34702e-5c2b-404b-97e9-f8b582260897" />



---

<div style="page-break-after: always;"></div>

[Back to Index](#index)

# Program 13: Directed Graph

## Aim
To write a Python program to implement Directed Graph.


## Program

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.neighbors = []


class Graph:
    def __init__(self):
        self.nodes = []

    def add_node(self, data):
        node = Node(data)
        self.nodes.append(node)
        return node

    def add_edge(self, node1, node2):
        node1.neighbors.append(node2)

    def print_graph(self):
        for node in self.nodes:
            print(node.data, "->", end=" ")
            for neighbor in node.neighbors:
                print(neighbor.data, end=" ")
            print()


graph = Graph()

A = graph.add_node("A")
B = graph.add_node("B")
C = graph.add_node("C")
D = graph.add_node("D")

graph.add_edge(A, B)
graph.add_edge(A, C)
graph.add_edge(B, D)
graph.add_edge(C, D)

graph.print_graph()

```

## Sample Output

<img width="145" height="107" alt="image" src="https://github.com/user-attachments/assets/8955e538-00cf-4141-a5ba-a68d962a6249" />

---

<div style="page-break-after: always;"></div>

[Back to Index](#index)

# Program 14: Undirected Weighted Graph

## Aim
To write a Python program to implement Undirected Weighted Graph.


## Program

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.neighbors = []


class Graph:
    def __init__(self):
        self.nodes = []

    def add_node(self, data):
        node = Node(data)
        self.nodes.append(node)
        return node

    def add_edge(self, node1, node2, weight):
        node1.neighbors.append((node2, weight))

    def print_graph(self):
        for node in self.nodes:
            print(node.data, "->", end=" ")
            for neighbor, weight in node.neighbors:
                print(neighbor.data, "(", weight, ")", end=" ")
            print()


graph = Graph()

A = graph.add_node("A")
B = graph.add_node("B")
C = graph.add_node("C")
D = graph.add_node("D")

graph.add_edge(A, B, 5)
graph.add_edge(A, C, 3)
graph.add_edge(B, D, 7)
graph.add_edge(C, D, 2)

graph.print_graph()

```

## Sample Output

<img width="321" height="102" alt="image" src="https://github.com/user-attachments/assets/084f900d-dc96-43ba-a56f-c05b15043644" />

---

<div style="page-break-after: always;"></div>

[Back to Index](#index)

# Program 15: Directed Weighted Graph

## Aim
To write a Python program to implement Directed Weighted Graph.


## Program

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.neighbors = []


class Graph:
    def __init__(self):
        self.nodes = []

    def add_node(self, data):
        node = Node(data)
        self.nodes.append(node)
        return node

    def add_edge(self, node1, node2, weight):
        node1.neighbors.append((node2, weight))
        node2.neighbors.append((node1, weight))

    def print_graph(self):
        for node in self.nodes:
            print(node.data, "->", end=" ")
            for neighbor, weight in node.neighbors:
                print(neighbor.data, "(", weight, ")", end=" ")
            print()


graph = Graph()

A = graph.add_node("A")
B = graph.add_node("B")
C = graph.add_node("C")
D = graph.add_node("D")

graph.add_edge(A, B, 5)
graph.add_edge(A, C, 3)
graph.add_edge(B, D, 7)
graph.add_edge(C, D, 2)

graph.print_graph()


```

## Sample Output

<img width="311" height="107" alt="image" src="https://github.com/user-attachments/assets/c36e5f3d-5335-46ab-9813-f0a4d6f50248" />


---

<div style="page-break-after: always;"></div>

[Back to Index](#index)

# Program 16: DFS 

## Aim
To write a Python program to implement DFS.


## Program

```python
class Graph:
    def __init__(self):
        self.graph = {}

    def add_edge(self, u, v):
        if u not in self.graph:
            self.graph[u] = []
        if v not in self.graph:
            self.graph[v] = []

        self.graph[u].append(v)
        self.graph[v].append(u)

    def DFS(self, start, visited=None):
        if visited is None:
            visited = set()

        visited.add(start)
        print(start, end=" ")

        for neighbor in self.graph[start]:
            if neighbor not in visited:
                self.DFS(neighbor, visited)


# Create graph
g = Graph()

g.add_edge(1, 2)
g.add_edge(1, 3)
g.add_edge(2, 4)
g.add_edge(2, 5)
g.add_edge(3, 6)

print("DFS Traversal:")
g.DFS(1)
```

## Sample Output

<img width="945" height="280" alt="image" src="https://github.com/user-attachments/assets/90ba657d-c286-4dde-969b-b9d334a4c5f0" />


---

<div style="page-break-after: always;"></div>

[Back to Index](#index)
# Program 17: BFS 

## Aim
To write a Python program to implement BFS.


## Program

```python
from collections import deque

class Graph:
    def __init__(self):
        self.graph = {}

    def add_edge(self, u, v):
        if u not in self.graph:
            self.graph[u] = []
        if v not in self.graph:
            self.graph[v] = []

        self.graph[u].append(v)
        self.graph[v].append(u)

    def BFS(self, start):
        visited = set()
        queue = deque([start])

        visited.add(start)

        while queue:
            node = queue.popleft()
            print(node, end=" ")

            for neighbor in self.graph[node]:
                if neighbor not in visited:
                    visited.add(neighbor)
                    queue.append(neighbor)


# Create graph
g = Graph()

g.add_edge(1, 2)
g.add_edge(1, 3)
g.add_edge(2, 4)
g.add_edge(2, 5)
g.add_edge(3, 6)

print("BFS Traversal:")
g.BFS(1)
```

## Sample Output

<img width="637" height="152" alt="image" src="https://github.com/user-attachments/assets/ae8fa696-0aa1-41f6-8be2-d46a5339b839" />


---

<div style="page-break-after: always;"></div>

[Back to Index](#index)

```









