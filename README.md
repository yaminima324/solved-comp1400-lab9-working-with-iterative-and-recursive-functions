Download Link: https://assignmentchef.com/product/solved-comp1400-lab9-working-with-iterative-and-recursive-functions
<br>
<strong>Triangular Numbers: </strong>If you arrange 15 dots in the shape of a triangle, you end up with an arrangement that might look something like this:

<ul>

 <li></li>

 <li></li>

 <li>•</li>

 <li>• •</li>

 <li>• • •</li>

</ul>




The first row of the triangle contains one dot; the second row contains two dots, and so on until the fifth row contains five dots. Whenever a row has more than one dot, there is a space between dots. As shown in the example that n = 5 has 15 (=1+2+3+4+5) dots, the number of dots it takes to form an n-row triangle in general is the sum of the integers from 1 through n. This sum is known as a <strong>triangular number</strong>.

Develop a program to first take a positive number <strong>n</strong> (greater than 0) from the user, and then calculate and output the value of the triangular number for <strong>n</strong>. Your design and implementation of the program must have one function to iteratively calculate the number with loop structure, and another function to obtain the same result but by calling the function itself recursively.

Your program should have    at least the following 3 functions (procedures):

<ul>

 <li>Use readNum()to take a valid number (greater than 0) from the user. This function has no input and returns a valid integer number <strong>n</strong> entered by the user.</li>

 <li>Use iterativeTriangularNumber(…)to calculates triangular number for <strong>n</strong> This function has one integer variable as an input, named<sub> number,</sub> and returns the value of the triangular number.</li>

 <li>Use recuriveTriangularNumbe(…)to calculates the triangular number for <strong>n</strong> This function has one integer variable as an input, named<sub> number,</sub> and returns the value of the triangular number.</li>

</ul>

<strong>Hint: </strong>As a base case, if number is equal to 1 then the triangular number of 1 is 1.




A Sample interaction is as follow:




Enter a valid number (&gt;0):     <u>-1</u>

Invalid number.

Enter a valid number (&gt;0):      <u>5</u>

Iterative: Triangular number of 5 is 15.

Recursive: Triangular number of 5 is 15.




<strong>Part A: RAPTOR Exercise </strong>

<ol>

 <li>Start RAPTOR and create the flowchart of Triangular Numbers.</li>

 <li>Save the flowchart to a file named “triangularNumbers.rap” in the working directory on the PC you are using.</li>

 <li>Demonstrate the triangularNumbers.rap file to GA/TAs and run with different input values.</li>

</ol>

<strong>Hint</strong>: The mode of your Raptor should be “Intermediate” to be able to add a procedure. <strong> </strong>

<strong> </strong>

<strong>Part B: C Programming Exercise </strong>

<ol>

 <li>Implement the algorithm as represented by “triangularNumbers.rap”, and write an equivalent C program that accomplishes what the flowchart does.</li>

 <li>Save your program to a file named “triangularNumbers.c” in the working directory on the PC you are using.</li>

 <li>Demonstrate the triangularNumbers.c file to GA/TAs and run with different input values.</li>

</ol>

<strong> </strong>

<strong>EVALUATION: </strong>

You need to show your GA/TA the complete programs at the end of this lab, or at the beginning of your next lab. The marks you will receive for this lab are made of two parts: Lab work marks 10 and attendance marks 5. <strong>Total 15 marks</strong>.

<strong>Lab Work Mark</strong>: Your C code will be evaluated based on your solutions for the problems based on the following scheme:

<ol>

 <li>Does the code run and meet specifications?

  <ul>

   <li>Is input adequate and input data type properly validated?</li>

   <li>Is processing adequate?</li>

   <li>Is output correct and adequate?</li>

   <li>Is the code compliable? Is the code run properly?</li>

  </ul></li>

 <li>Is the code properly commented?

  <ul>

   <li>Is the program title, programmer’s first and last name, and the date posted at the top in a multi-line comment?</li>

   <li>Is each significant step of the program properly commented?</li>

   <li>Are comments added to clarify details?</li>

   <li>Are comments clear, accurate, neatly formatted, and have no misspellings?</li>

  </ul></li>

 <li>Is the code properly formatted?

  <ul>

   <li>Are blocks of code indented according to their parent-child relationship?</li>

   <li>Do curly braces line up vertically?</li>

   <li>Is there an empty line between significant steps (blocks) of the program?</li>

   <li>Is the width of the code contained within a reasonable limit so that minimal horizontal scrolling is required (with 800 x 600 monitor resolution), and there is minimal linewrapping when printed?</li>

   <li>Is camel-case notation used for variable, e.g. employeeLastName?</li>

  </ul></li>

</ol>