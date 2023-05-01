Download Link: https://assignmentchef.com/product/solved-cecs326-homework-18
<br>
Chapter 12

Purpose: This assignment provides experience with working sets.

Write a program the reports out the working set and working set size. The program should contain a procedure that prints the “time”, “working set size” and “working set”. The following illustrates the output expected:

Time Size Set

<ul>

 <li>3 7 2 4</li>

 <li>2 7 2</li>

 <li>3 7 2 5</li>

</ul>

I give you the main program to use and a stub for the function in the file workingset.cpp found in my 326 directory. The start is a special case which you should skip. You should start when you have enough entries to form the window, that is if your window size is 6, start computing the working set when at time 5. (See the loop format in the sample code.)

Suggestions: Use C++. You need a main loop, I show you how to do this in the sample code. Inside this loop declare an STL vector. Since the vector is inside the loop it will be reinitialized each round of the loop to be empty. Build your working set in this vector. Check each page in the window (a nested loop); if the page is in the vector, do nothing; if it is not, append it (push_back). When you are done the vector will have the working set. Print the time, the size of the vector and the vector contents.

Demo:Your workingset code. The instructor will also examine what code you filled in to the stub.