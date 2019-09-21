# python-basic-code
Fundamentals of python code available here related to list
l=[1,2,3,4,5]
print(l)
#*******************************************triangle*****
# find different type of triangle  by taking input from user
print(" Give input lengths of the triangle sides: ")
a = float(input("x: "))   #side of triangle 
b = float(input("y: "))    #side of triangle
c = float(input("z: "))   #side of triangle

if a == b == c:
	print("Equilateral triangle")
elif a==b or b==c or c==a:
	print("isosceles triangle")
else:
	print("Scalene triangle")


#******************************************* centroid of triangle*****
# To find  the centroid of triangle 	 
if __name__ == "__main__" : 

	# coordinate of the vertices 
	x1, x2, x3 = 2, 6, 12
	y1, y2, y3 = 4, -8, -14
	
	# Formula to calculate centroid 
	x = round((x1 + x2 + x3) / 3, 1) 
	y = round((y1 + y2 + y3) / 3, 1) 

	print("Centroid =","(",x,",",y,")") 


