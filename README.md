Download Link: https://assignmentchef.com/product/solved-ece39595-homework-4
<br>
<strong>Part A: </strong>

Using the code in the directory PartA, convert Vehicle to be an abstract class. Make all functions that are overridden with different functionality in HondaFit and FordF350 pure virtual functions. Make functions that have the same functionality in HondaFit and FordF350 concrete functions with implementation.

Make sure the program compiles and runs with the same output as in HW2.

<strong>Part B: </strong>

In the PartB directory there is a Makefile and some C++ code that doesn’t compile.  This homework will have three steps, which you will perform by editing the code in PartB.  You will turn in only the final code.

<strong>Step 1: get the program to compile </strong>

<strong>Step 2: (you may end up doing some of these as part of Step 1, that’s ok</strong>)

<ol>

 <li>Modify the Address constructor so that its body (what is between the “{“ and “}”) is empty and use initializer lists to do all initialization.</li>

 <li>Modify the Person constructor so that the body only contains the initialization of dateOfBirth, but all initializations are done.</li>

 <li>Modify the Employee constructor so that its body is empty but all initializations are done.</li>

 <li>Enable all functions to be callable as virtual functions.</li>

 <li>Any other changes you need to make to get the desired output (see below).</li>

</ol>

<strong>Step 3: Convert the program to use no pointers and no </strong>new<strong> operations, i.e. use object variables whenever possible </strong>

The output of Part B when finished will look like:

add1:

1281 Gruene Rd

Greune

TX

78130  add2:

801 Bldg

Yorktown Heights

NY

10598




Employee1: Employee, Jerry Jeff Walker, 78130

Employee2: Employee, Fran Allen, 10598