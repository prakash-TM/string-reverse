## String Reverse without reverse the numbers in JS

## Question :

### Given a string that contains words seperated by digits(0-9). Reverse words in place
### Eg: asd1fa -> dsa1af


## Algorithm :
 - step1: get the string as the variable name is str
 - step2: declare empty array named arr
 - step3: convert str in to the array as named arr and add number string(like '1') in that str
 - step4: declare two empty strings named as it_str and rev
 - step5: assign a for loop and iterate the arr
 - step6: check is the iterable element is present in alphabets a to z
 - step7: if yes push in to the it_str string
 - step8: if not,
    - step8.1: split the it_str and stored variable spl
    - step8.2: reverse spl string and stored rev_arr
    - step8.3: join rev_arr and stored variable res
    - step8.4: concat variables rev and res
    - step8.5: make empty variable it_str
    - step8.6: concat array element to rev
 - step9: remove the last element in the rev string
 - step10: return rev
