Arrays
=============
_Definition:_ Which is a collection of elements of same type and data stored in continuous memory locations.

## Types
1. Static
2. Dynamic

Advantages:
 1. Random access
 2. Constant time for read and write operations

Disadvantages:
  1. Size limitations

Example:

We are using low level language to illustrate all concepts
```c
int arr[3];

int arr[]={1,2};
```
## How it looks in memory
Coming soon...

## Accessing

Let us assume an array numbers with size 4  
Every element in array should be the same size  

If you want to access `nth` element then `nth` element is calculated by simple arithmetic operations as below
```
nth_element_address=array_address+element_size*(n-first_index)
```

For above array number If I want to access 2nd element  
**Assume**,   
array_address = 1000,  
n=2,  
first_index=0,  
element_size=4.
Then second_element_address=1008.

## Operations - Time
1. pushFront -  O(1)
2. pushBack  -  O(n)
3. popBack   -  O(1)
4. popFront
5. isEmpty
6. pushBeforeNthElement
7. pushAfterNthElement
