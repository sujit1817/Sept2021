# Sept2021
1) What do you mean by Data Structures?                                                                                                                                           
Data Structure can be defined as the group of data elements which provides an efficient 
way of storing and organising data in the computer.
or we can say
it is a way to store data into the memory (i.e. into the main memory) in an organized manner so
that operations (like insertion, deletion, searching, sorting, traversal etc....) can be performed on it
efficiently.

2) Define The Goals Of Data Structure?                                                                                                                                           
 Identify and develop useful mathematical entities and operations and to determine what classes of problems 
can be solved by using these entities.


3) What is the Need of DS?                                                                                                                                                       
Data struture provides a way of organizing ,managing and storing data efficienty with help
of data strutures.
provides efficiency
reusability


4) List out the areas in which data structures are applied extensively(real time examples)?                                                                                      1.Database Management System                                                                                                                                            
2.Books placed one over another(stack)                                                                                                                                           
3.ticket booking system(queue).// 1st come(in) first serve(Out)//  (FIFO)


5) List different types of data structures.                                                                                                                                    
   Basically, data structures are divided into two categories:
     
1. linear/basic data structures: data ele's gets stored in a linear manner and hence can be accessed
in a linear manner.
- array ( Array is an object which contains elements of a similar data type )
- linked list ( it is a collection/list of logically related similar type of elements )
- stack (It works just like a Books placed one over another where the last book kept will be removed first)
- queue (It works just like a queue of people in the ticket counter where first person on the queue will get the ticket first.)

2. non-linear/advanced data structures: data ele's gets stored in a non-linear manner and hence
can be accessed in a non-linear manner.
- tree (heirachical manner) // one branch extends another one
- graph (network)
- hash table (associative manner)

6) What Does Abstract Data Type Mean?                                                                                                                                           --> The Data Type is basically a type of data that can be used in different computer program. It signifies the type like integer, float etc, the space like integer will take 4-bytes, character will take 1-byte of space etc.

--> The abstract datatype is special kind of datatype, whose behavior is defined by a set of values and set of operations. The keyword “Abstract” is used as we can use these datatypes, we can perform different operations. But how those operations are working that is totally hidden from the user. The ADT is made of with primitive datatypes, but operation logics are hidden.                                                                                                                                                     
Some examples of ADT are Stack, Queue, List etc.                                                                                                                            


7) What is Recursion?                                                                                                                                                           
The process in which a function calls itself directly or indirectly is called recursion and 
the corresponding function is called as recursive function.

8) List and Explain types of Recursion
Direct Recursion.
Indirect Recursion.
Tail Recursion.
Head Recursion. 

1)Direct Recursion                                                                                                                                                               
In the direct recursion, only one function is called by itself.

2)Indirect Recursion                                                                                                                                                             
In indirect recursion more than one function are called by the other function.

3)Tail Recursion                                                                                                                                                                 
A recursive function is tail recursive when a recursive call is the last thing executed by the function.

4)Head Recursion                                                                                                                                                                 
If a recursive function calling itself and that recursive call is the first statement in the function then it's known as Head Recursion

9) Explain the data structures used to perform recursion?                         



10)List the examples where recursion is used
Recursion is made for solving problems that can be broken down into smaller, repetitive problems. helps in reducing code length.
- Adding a list of numbers.
- factorial of a number.


11)Explain the difference between Recursion and Iteration, justify which to use when,Tail recursion?
Recursion
- A program is called recursive when an entity calls itself. 
- Used when code size needs to be small, and time complexity is not an issue.
- 	Smaller code size
- 	Very high time complexity

Iteration
- A program is call iterative when there is a loop (or repetition)
- Used when time complexity needs to be balanced against an expanded code size.
- 	Larger Code Size.
- 	Relatively lower time complexity


12)Difference between Primitive and Non Primitive DS
Data structure means organizing the data in the memory. The data can be organized in two ways either linear or non-linear way.
There are two types of data structure available for the programming purpose:

1.Primitive data structure ( int , float, character )
2.Non-primitive data structure ( array, linked list, stack )

Primitive data structure is a fundamental type of data structure that stores the data of only one type. 
whereas, the non-primitive data structure is a type of data structure which is a user-defined that stores the data of different types in a single entity.


13)Difference between Linear and Non Linear DS
 1. In a linear data structure, data elements are arranged in a linear order where each and every elements are attached to its previous and next adjacent.
Arrray , list, stack, queue.

 2. In a non-linear data structure, data elements are attached in hierarchical manner.
 Tree, Graph
 

14)What are different characterstics of an Algorithm?types of Algorithm.
Finiteness: An algorithm should have finite number of steps and it should end after a finite time.
Input: An algorithm may have many inputs or no inputs at all.
Output: It should result at least one output.
Definiteness: Each step must be clear, well-defined and precise.
Effectiveness: Each step must be simple and should take a finite amount of time

Brute Force Algorithm: 
This is the most basic and simplest type of algorithm. A Brute Force Algorithm is the straightforward approach to a problem i.e., the first approach that comes to our mind on seeing the problem. More technically it is just like iterating every possibility available to solve that problem.

Recursive Algorithm:
This type of algorithm is based on recursion. In recursion, a problem is solved by breaking it into subproblems of the same type and calling own self again and again until the problem is solved with the help of a base condition.

Divide and Conquer Algorithm:
In Divide and Conquer algorithms, the idea is to solve the problem in two sections, the first section divides the problem into subproblems of the same type. The second section is to solve the smaller problem independently and then add the combined result to produce the final answer to the problem.
eg. Binary Search, Merge Sort, Quick Sort.

Dynamic Programming Algorithms:
This type of algorithm is also known as the memoization technique because in this the idea is to store the previously calculated result to avoid calculating it again and again. In Dynamic Programming, divide the complex problem into smaller overlapping subproblems and storing the result for future use.

15)State Advantages and Disadvantages of Recursion.                                                                                                                             

Advantages:
makes code shorter
reduces the time needed to write

disadv:                                                                                                                                                                         
Hard to analyze or understand the code.
It usually uses more memory for the stack.
Can lead to stack overflow


//just for information
//the time complexity is the amount of time taken by an algorithm to run
