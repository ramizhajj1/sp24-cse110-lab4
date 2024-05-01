1. 3 is printed.  
2. There is a ReferenceError: discountedPrice is not defined. This occurs because the variable is only accessible within the loop, not after it is completed.  
3. It prints 150.  
4. It returns [50, 100, 150]  
5. There is a ReferenceError because i is not defined outside of the loop.  
6. There is a ReferenceError because discountedPrice is not defined outside of the loop.  
7. It will log 150 because the last price is 300, and the discounted price is calculated at 300(1-0.5) = 150.  
8. The code successfully computes the discounted prices, rounds them, and returns the final array of these values [50, 100, 150].  
9. There is a ReferenceError because the let declaration of i limits its visibility to within the for loop, making it undefined in the context where the console log statement is called.  
10. It will print 3 because given the input prices = [100, 200, 300], length would be 3 because there are three items in the prices array.   
11. It computes the discounted prices for each element in the input array using the provided discount factor, stores them in an array, and returns this array, printing the array [50, 100, 150].  
12. A. student name  
B. student['Grad Year']
C. student.greeting()  
D. student['Favorite Teacher'].name
E. student.courseLoad[0]
13. A. It prints 32 because when you use the + operator and one of the operands is a string, the other operand is converted to a string and then concatenated. Thus, the number 2 is converted to the string '2', and then concatenated with '3'.
B. It prints 1 because  the - operator is not valid for strings in a context that expects a number. Therefore, JavaScript tries to convert both operands to numbers. '3' successfully converts to 3, and 2 is already a number, so the operation performed is 3 - 2.
C. 3 because null is 0 and 0+3 is 0.
D. 3null because it prints 3+null printed.
E. 4 because true is converted to 1 and 1+3 is 4. 
F. 0 because false and null are both converted to 0. 
G. 3undefined becausethe string undefined is concatenated with 3. 
H. NaN because undefined cannot be converted to a number.  
14. A. True because 2 is greater than 1.  
B. False because 2 is considered larger than 1. 
C. True because == is a type coercion and 2 is equal to 2.  
D. False, becaise there is no type coercion as === is strict, so a number cannot be equal to a string.  
E. False, because true is converted to 1, which is not equal to 2 so it is false.  
F. true, because Boolean(2) is evaluated to true and since both are boolean true it returns a result true.  
15. The == operator performs an equality check between two values after converting them to a common type (type coercion), which can lead to unexpected results if the implicit conversion rules are not well understood. For example, 0 == '0' returns true because the string is converted to a number. In contrast, the === operator, known as the strict equality operator, checks for equality without type coercion, requiring both the value and the type to be the same for it to return true. Thus, 0 === '0' results in false since no conversion is attempted and the types differ.  
17.   Inside modifyArray, a new empty array newArr is initialized. The function then iterates through each element of the input array [1, 2, 3].  For each element in the array, the doSomething function is called with the current element as its argument.
doSomething takes a number (num) and returns it multiplied by 2.
For 1: doSomething(1) returns 2.
For 2: doSomething(2) returns 4.
For 3: doSomething(3) returns 6.The result of each callback execution is then pushed into newArr.
After processing 1, newArr becomes [2].
After processing 2, newArr becomes [2, 4].
After processing 3, newArr becomes [2, 4, 6].  Once all elements have been processed, the modified array [2, 4, 6] is returned from the modifyArray function.  
SO the result is [2,4,6].  
19. The optput is  
1  
4  
3  
2.
