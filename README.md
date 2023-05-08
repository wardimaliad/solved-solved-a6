Download Link: https://assignmentchef.com/product/solved-solved-a6
<br>
Write a simple function template for predicate function isEqualTo that compares its two arguments of the same type with the equality operator (==) and returns true if they are equal and false if they are not equal. Use this function template in a program that calls isEqualTo on a variety of built-in types and user define types, Complex and Date (need to overload the equality operator (operator==) and extraction operator (operator&lt;&lt;)). Write a program with variety of inputs to test the functionalities of the program.

The following are classes, functions, and private data members needed in this program. You can add and create more classes, functions and private data members for this program.

Date class

There should have three private integer data members, month, day and year for the Date class.

It should have Date, operator&lt;&lt; and operator== functions in the class. The Date class has to do a validation on data.

Complex class

There should have two private double data members, real and imaginary for the Complex class.

It should have Complex, operator&lt;&lt; and operator== functions in the class.

CISP400V9A6.cpp

Implement an isEqualTo template function to test with different types.

The data type and data are list as follow:

Data typeOperant 1Operant 2Int11Int24Int-11Int-1-1charaacharaccharcacharccdouble2.22.2double2.22.3double-2.22.2double-2.2-2.2Complex(10, 5)(10, 5)Complex(10, 5)(10, 54)Complex(10,- 5)(10, 5)Complex(-10, -5)(-10, -5)stringabcdefgabcdefgstringabcdefgabcdefhString-abcdefgabcdefgstring-abcdefg-abcdefgDate(2, 31, 2017)(2, 31, 2017)Date(2, 13, 2017)(2, 14, 2017)Date(2, 13, 2017)(2, 13, 2017)Date(2, 13, 2017)(2, 13, 2017)

Display the data type they are testing in a group and use the isEqualTo function to thes the equality of the operants.

This assignment comes with a CISP400V9A6.zip file. It includes CISP400V9A6.exe file. The CISP400V9A6.exe file is an executable file. You can double click the file to get to the expecting result (see the picture below) of this assignment. You can choose any Date class and Complex class from the textbook to start the program. You also need to follow the specification for the CISP400V9A6.cpp to do the driver to test the program. After you finish your implementation for the Complex class, Date class and CISP400V9A6.cpp, you can put the CISP400V9A6.cpp, Date.h, Date.cpp, Complex.h and Complex.cpp in a project and then you can run to the same result as the CISP400V9A6.exe.

The following is a display of the expecting results.

Please document CISP400V9A6.cpp, Date.h, Date.cpp, Complex.h and Complex.cpp files properly and zip them into a proper named zip file for an assignment (refer to the assignment section of the class syllabus) and submit it to the A6 dropbox of the D2L Website.

Worth 150 points

AD6

Modify a stack template class from chapter 19 to push a variety of built-in types and a user define types into a variety of built-in types’ and user define types’ stacks ( such as ints to int stacks, and chars to char stacks) and pop them out to do a comparison.

Display procedures, type of data by using typeid( ).name(), data are compared, and equal or not equal of the data.

There are Complex, Date and Employee user defied data type(need to overload the equality operator (operator==) and extraction operator (operator&lt;&lt;)) in this program. Write a program with variety of inputs to test the functionalities of the program.

The following are classes, functions, and private data members needed in this program. You can add and create more classes, functions and private data members for this program.

Date class

There should have three private integer data members, month, day and year for the Date class.

It should have Date, operator&lt;&lt; and operator== functions in the class. The Date class has to do a validation on data.

Complex class

There should have two private double data members, real and imaginary for the Complex class.

It should have Complex, operator&lt;&lt; and operator== functions in the class.

Employee class

The Employee class has two private string data members (firstName and lastName) and one private Date object (birthDate).

It has Employee, operator&lt;&lt; and operator== public functions in the class.

Stack class

This is a template class you can get it from the textbook example to make adjustments.

The stack class has two private integers( size and top0 and 6 elements array pointer(stackPtr[6]) point to any declare data type in the textbook case is T.

There should have public Stack, push and pop functions in the class.

CISP400V9AD6.cpp

In here you need to create couple stacks for each data type and push the data into stacks and pop them out to do comparison.

For integers: After push all numbers into two integers stacks, the two stacks should look like the following.

5

5

4

4

3-13-12-12112140101Stack1Stack2

For chars: After push all charts into two char stacks the two stacks should look like the following.

5

5

4

4

3A3A2A2a1a1c0a0aStack1Stack2

For doubles: After push all doubles into two double stacks the two stacks should look like the following.

5

5

4

4

3-2.23-2.22-2.222.212.212.302.202.2Stack1Stack2

For Complex: After push all Complex objects into two Complex stacks the two stacks should look like the following.

5

5

4

4

3(10, -5)3(10, -5)2(10, -5)2(10, 5)1(10, 5)1(10, 54)0(10, 5)0(10, 5)Stack1Stack2

For string: After push all string objects into two string stacks the two stacks should look like the following.

5

5

4

4

3-abcdefg3-abcdefg2-abcdefg2abcdefg1abcdefg1abcdefh0abcdefg0abcdefgStack1Stack2

For Date: After push all Date objects into two Date stacks the two stacks should look like the following.

5

5

4

4

3(-2, 13, 2017)3(-2, 13, 2017)2(-2, 13, 2017)2(2, 13, 2017)1(2, 13, 2017)1(2, 14, 2017);0(2, 31, 2017)0(2, 31, 2017)Stack1Stack2

For Employee: After push all Employee objects into two Employee stacks the two stacks should look like the following. (ed1 and ed2 are Date objects. The ed1’s value is (3,1,2014), and ed2’s value is (3,2,2014).)

5(“1John”, “1Lin”, ed2);

5(“1John”, “1Lin”, ed2);4(“John”, “1Lin”, ed1);4(“John”, “Lin”, ed2);3(“John”, “Lin”, ed1);3(“John”, “1Lin”, ed2);2(“John”, “1Lin”, ed1);2(“John”, “Lin”, ed1);1(“1John”, “Lin”, ed1);1(“John”, “Lin”, ed1);0(“John”, “Lin”, ed1);0(“John”, “Lin”, ed1);Stack1Stack2

In the program you need to display the steps that your program goes through. Such as in the Employee test area should show

**Employee-Employee Testing Employee objects Employee-Employee**”

Create two Employee-stacks.

Push Date objects into the Date-stacks.

Push them into Date stack

Pop out Employee objects from the Employee-stacks to do comparison.

After that use a while loop to pop out the stacks, display “Objects of“ and use” typeid( ).name()” to show class name. Use cout&lt;&lt; to diplay data and use == to test if the two data same or not.

This assignment comes with a CISP400V9AD6.zip file. It includes CISP400V9AD6.exe file. The CISP400V9AD6.exe file is an executable file. You can double click the file to get to the expecting result (see the picture below) of this assignment. You can choose any Employee class, Date class and Complex class from the textbook to start the program. You also need to follow the specification for the CISP400V9AD6.cpp to do the driver to test the program. After you finish your implementation for the Complex class, Employee class, Date class and CISP400V9A6.cpp, you can put the CISP400V9A6.cpp, Date.h, Date.cpp, Employee.h, Employee.cpp, Complex.h and Complex.cpp in a project and then you can run to the same result as the CISP400V9AD6.exe.

The following is a display of the expecting results.