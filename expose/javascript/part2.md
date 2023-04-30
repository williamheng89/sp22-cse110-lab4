1. console log will display 3 because the for-loop will increment i to 3 and we are able to access this variable outside the loop because of the var keyword
2. console log will display 150 because the last time discountedPrice was reassigned was during the last loop cycle where i = 2 and prices[i] = 300 and discountedPrice = 300 * (.5) = 150. We are able to access this variable because of the var keyword
3. console log will display 150 because the last time final price was reassigned was during the last loop cycle where i = 2 and discountedPrice = 150. Math.round(150 * 100) / 100 = 150. We are able to access this variable because of the var keyword
4. function will return [50, 100, 150] because we are finding the price of a product after applying a discount to it and then pushing those amounts to an array called discounted which is being returned. This function is returning a copy of the prices array after applying the discount to all the items in it. 
5. console log will display ERROR because the variable has the let keyword and we are out of its available scope (within the for-loop) when we tried to access it.
6. console log will display ERROR because the variable has the let keyword and we are out of its available scope (within the for-loop) when we tried to access it.
7. console log will dispaly 150 because the last time final price was reassigned was during the last loop cycle where i = 2 and discountedPrice = 150. Math.round(150 * 100) / 100 = 150. We are able to access this variable because we are in the scope of the variable.
8. function will return [50, 100, 150] because we are finding the price of a product after applying a discount to it and then pushing those amounts to an array called discounted which is being returned. This function is returning a copy of the prices array after applying the discount to all the items in it. There is also no mal scope accesses.
9. console log will display ERROR because the variable has the let keyword and we are out of its available scope (within the for-loop) when we tried to access it.
10. console log will display 3 because length = prices.length which is 3. 
11. function will return [50, 100, 150] because we are finding the price of a product after applying a discount to it and then pushing those amounts to an array called discounted which is being returned. This function is returning a copy of the prices array after applying the discount to all the items in it. Even though the function returns discount, an array variable with the keyword const, this does mean that the variable is unable to be reassigned, but does not mean its contents are immutable. 
12. a: student.name
    b: student['Grad Year']
    c: student.greeting()
    d: student['Favorite Teacher'].name
    e: student.courseLoad[0]
13. a: '32' becuase when we use the '+' symbol, JS implicitly converts the numbers to strings to be concatenated
    b: 1 because when we use the '-' symbol, JS implicitly converts the strings to numbers to be performed on
    c: 3 because when we use the '+' symbol, JS implicitly converts null to value 0 and 3 + 0 = 3
    d: '3null' because when we use the '+' symbol, JS implicitly converts null to a string with value 'null' and concatenates with the string '3'
    e: 4 because true maps to 1 and 1 + 3 = 4
    f: 0 because they both get converted to numbers with value 0 and 0 + 0 = 0
    g: '3undefined' becayse when we use the '+' smbol, JS implicitly converts undefined to a string with value 'undefined' and concatenates with the string '3'
    h: NaN because when we use the '-' symbol, JS implicitly converts the strings to numbers and undefined is "Not a Number" and any arithmetic with NaN results in NaN
14. a: true because when we use the '>' symbol on a string and a number, JS implicitly converts the strings to nymbers and 2 > 1 is true
    b: false because when we use the '<' symbol on two strings, they get compared lexigraphically and '2' comes after '1'.
    c: true because when we use the '==' comparison a number and a string, JS implciitly converts the strings to numbers to be compared and 2 == 2 is true
    d: false because when we use the '===' comparison, JS checks equality without any type conversions and thus 2 and '2' are different types so it outputs false
    e: false because when we use the '==' comparison, JS implicitly comverts true to 1 before performing the comparison and 1 == 2 is false
    f: true because when we use the '===' comparison, JS checks without type conversions (they are same type) and their values are the same (true) true == true.
15. '==' has implicit conversions before checking equality meanwhile '===' checks without type conversions
16. part2-question16.js
17. [2,4,6] here we are passing in a function as a parameter. The fucntion modifyArray is taking in the array [1,2,3] and creates a new empty array which will be filled out and returned. modifyArray then iterates over the passed in array, applies the doSomething function onto those elements (multiplies them by 2) and then pushes that product onto the array which is returned at the end.
18. part2-question18.js
19. 1
    4
    3
    2