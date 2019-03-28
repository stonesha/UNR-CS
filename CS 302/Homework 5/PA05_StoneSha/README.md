# Proj 5 Documentation

## Style
I used the STL library to make heaps out of vector and various functions concerning them; pushing, popping, and sorting.
Using namespace std; was used for convenience sake since I didn't want to type it out all the time. Comments in the 
.cpp file are self-explanatory.

## Console Log
```
=====Randomly Generated Vector=====

20, 267, 255, 178, 169, 253, 135, 0, 290, 251,
5, 199, 78, 194, 99, 231, 51, 96, 226, 86,
219, 29, 119, 211, 266, 101, 168, 208, 169, 43,
4, 124, 182, 155, 262, 160, 218, 209, 101, 101,
51, 50, 123, 273, 231, 2, 67, 173, 149, 171,
101, 196, 143, 53, 172, 288, 256, 85, 139, 0,
202, 294, 281, 98, 262, 234, 95, 293, 196, 43,
248, 136, 124, 215, 299, 211, 159, 175, 293, 234,
188, 200, 9, 275, 227, 237, 279, 76, 175, 211,
276, 1, 22, 148, 104, 71, 19, 143, 92, 103,
=====Vector is now a Heap=====
=====Mean pushed onto Heap=====
Mean is 158

299, 293, 294, 293, 279, 266, 288, 262, 290, 275,
276, 253, 196, 256, 281, 262, 248, 267, 226, 234,
251, 273, 148, 211, 199, 143, 172, 255, 169, 202,
135, 231, 234, 196, 43, 160, 218, 211, 178, 188,
200, 227, 237, 175, 231, 22, 119, 173, 149, 171,
101, 101, 78, 53, 168, 208, 194, 85, 139, 0,
43, 4, 99, 98, 124, 182, 95, 155, 51, 20,
0, 136, 124, 215, 96, 209, 159, 175, 101, 101,
86, 51, 9, 50, 169, 219, 123, 76, 5, 211,
29, 1, 2, 67, 104, 71, 19, 143, 92, 103,
158,
=====Maximum Element Deleted=====

294, 293, 288, 293, 279, 266, 281, 262, 290, 275,
276, 253, 196, 256, 202, 262, 248, 267, 226, 234,
251, 273, 148, 211, 199, 143, 172, 255, 169, 158,
135, 231, 234, 196, 43, 160, 218, 211, 178, 188,
200, 227, 237, 175, 231, 22, 119, 173, 149, 171,
101, 101, 78, 53, 168, 208, 194, 85, 139, 0,
43, 4, 99, 98, 124, 182, 95, 155, 51, 20,
0, 136, 124, 215, 96, 209, 159, 175, 101, 101,
86, 51, 9, 50, 169, 219, 123, 76, 5, 211,
29, 1, 2, 67, 104, 71, 19, 143, 92, 103,
=====Sorted Heap=====

0, 0, 1, 2, 4, 5, 9, 19, 20, 22,
29, 43, 43, 50, 51, 51, 53, 67, 71, 76,
78, 85, 86, 92, 95, 96, 98, 99, 101, 101,
101, 101, 103, 104, 119, 123, 124, 124, 135, 136,
139, 143, 143, 148, 149, 155, 158, 159, 160, 168,
169, 169, 171, 172, 173, 175, 175, 178, 182, 188,
194, 196, 196, 199, 200, 202, 208, 209, 211, 211,
211, 215, 218, 219, 226, 227, 231, 231, 234, 234,
237, 248, 251, 253, 255, 256, 262, 262, 266, 267,
273, 275, 276, 279, 281, 288, 290, 293, 293, 294,
Process returned 0 (0x0)   execution time : 1.142 s
```