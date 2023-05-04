Download Link: https://assignmentchef.com/product/solved-csce-155a-homework-assignment-3-gradebook-ii
<br>
The objectives of this homework assignment:

1. Master conditional and looping logic flow in Java.

2. Familiarize with the use of <strong>arrays</strong>

a. Manipulate a collection of data values using an array

b. Compute statistics out of an array of values

c. Declare and use an array of primitive data types

3. Familiarize with the use of <strong>exception handling</strong> for data format and range checking

4. Master code documentation, compilation, and execution

5. Expose to Java syntax, programming styles, and a Java class.

Draw a flowchart for the algorithm and write a program that processes the statistics for grades for a group of students in the CSCE155A class. In order to do this, you need to store this information in a Java two-dimensional array of values representing points earned in the class. Dimension 1 represents the students and dimension 2 represents the categories of points, which is as follows:

Homework Assignments (25%) – 600 points possible [6 assignments x 100 points each]

Labs (25%) – 600 points possible [15 labs x 40 points each]

Midterms (25%) – 600 points possible [2 exams x 300 points each]

PRS Test (4.17%) – 100 points possible

Extra Credit (10.42%) – 250 points possible

Final Exam (20.83%) – 500 points possible
 You will randomly generate the points for each category according to its maximum possible points. Your program will first take in an integer as input, which will be the seed to your random number generator. Then you would simply need to inquire from the user number of students in the class. Your program will use this information to randomly generate the points and fill the array. <em>Note: You cannot use JCF classes or any standard classes to store the data values.</em>

The grading scale for this course is as followed:

• A+ &gt;= 96.67%

•A    &gt;= 91.71%

• A- &gt;= 90.04%

• B+ &gt;= 86.71%

•B   &gt;= 81.71%

• B- &gt;= 80.04%

• C+ &gt;= 76.71%

• C &gt;= 71.71%

• C- &gt;= 70.04%

• D+ &gt;= 66.71%

• D &gt;= 61.71%

• D- &gt;= 60.04%

• F &lt; 60.03%

You are given the following set of <em>minimum</em> requirements to design and implement the overall grade processing application that stores the points in each category for each specific student.

Grade values should be a random integer between one half of the maximum grade in the category and the maximum grade in the category (e.g. in “Assignments”, the value should be a random integer between 300 and 600, inclusively).

Program should be able to accept at least two (2) students and up to one hundred (100) students.

Program should properly handle any exceptions that could be thrown during the processing of user input/entry.

For the seed to work correctly for the example below and for the Webgrader, you need to use the <strong>Random</strong>class in Java. Create an instance of this standard class with the inputted seed value and use its appropriate methods to generate your random numbers to fill your array.

Need to be able to nicely print the table of information. This information needs to be stored in a Java two-dimensional array with individual grade elements for each student in each category. <em>Note: You cannot use JCF classes or any standard classes to store the data values.</em> You are also expected to properly handle any exceptions that could be thrown during the processing of your array.

Need to print the total points, percentage, and letter grade earned by each student. The percentage needs to be rounded to two decimal places.

Need to print the students having made the most and least points over all categories combined (e.g. student with the highest grade and student with the lowest grade).

Need to print the average, maximum, minimum, and total points earned in each category. Average should be rounded to and displayed as two decimal places.

Program should repeat by allowing the user to enter in another number of students.