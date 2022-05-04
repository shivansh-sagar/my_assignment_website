# python program
arithmatic and logical operation usin if and else statement



print("Arithmatic operation ==> 1")
print("Logical operation    ==> 2")
choice=int(input("Enter the operations:"))
  
if choice==1:
    num1 = input('Enter first number: ')  
    num2 = input('Enter second number: ')
    sum = float(num1) + float(num2)  
    min = float(num1) - float(num2)  
    mul = float(num1) * float(num2)  
    div = float(num1) / float(num2)  
    print('The sum of {0} and {1} is          =====> {2}'.format(num1, num2, sum))  
    print('The subtraction of {0} and {1} is  =====> {2}'.format(num1, num2, min))  
    print('The multiplication of {0} and {1} is ===> {2}'.format(num1, num2, mul))  
    print('The division of {0} and {1} is     =====> {2}'.format(num1, num2, div))  
elif choice==2:
    num1=int(input("Enter the number between 0-100:"))
# AND Example
    if num1 < 60 and num1 > 20:
	    print("you are enter number between 20-60")
    
# OR Example
    if num1 < 20 or num1 > 60:
	    print(" you enter number less than equal to20 OR greater than equal to 60 ")
	
	    
    elif num1 >100:
        print("you enter number greater than 100")
    
    else:
        print("Error")
	  
