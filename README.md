# Determine-the-sides-of-Triangle

side1=int(input("enter the side1"))
side2=int(input("enter the side2"))
side3=int(input("enter the side3"))
#determine the type of triangle
if side1==side2==side3 :
    print("EQUILATERAL TRIANGLE")
elif side1 == side2 or side2 == side3 or side1 ==side3:
    print("ISOSCELES TRIANLGE")
else:
    print("SCALENE TRIANGLE")
