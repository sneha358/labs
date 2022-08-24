# labs
different programs.
## 2nd largest element in 2d array ...

import numpy as np
arr = np.array([[1,5,4],[3,8,6],[38,19,10]])
print (arr)
arr1 = arr.flatten()
print(arr1)   
arr2 = arr1.sort()
print(arr1)
print(arr1[7])


## find type of triagle by length

a = int(input("give 1st side of triangle"))
b = int(input("give 2nd side of triangle"))
c = int(input("give 3rd side of triangle"))

def is_valid_triangle(a,b,c):
    if a+b>=c and b+c>=a and c+a>=b:
        return True
    else:
        return False

print(is_valid_triangle(a,b,c))

def type_of_triangle(a,b,c):
        if (a**2 == b**2 + c^2 or b**2 == a**2 + c**2 or c**2 == a**2 + b**2):
            print("it is a right angle triangle")
        elif (a**2 > b**2 + c**2 or b**2 > a**2 + c**2 or c**2 > a**2 + b**2 ):
            print("it is a obtuse angle triangle")
        else:
            print("it is a acute angle triangle")
        
    

if is_valid_triangle(a,b,c):
    type_of_triangle(a,b,c)


        

