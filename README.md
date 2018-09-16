# dsba-ha
# problem 1 : date recognizer

import re

input_str = input()


x = re.match(r'[\d\d{2}\d{4}]+[\.|\-|\/|\:][\d\d{2}\d{4}]+[\.|\-|\/|\:][\d\d{2}\d{4}]+', input_str)


if x:
        
        print("yes")
    
else:
        
        print ("no")
    
    
# problem 2 : email recognizer

import re

input_str = input()

x = re.match(r'[^@]+@[^@]+\.[^@]+', input_str)

if x:

     print("yes")
    
else:

     print ("no")



