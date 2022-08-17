#Input and Output 
#input()
from datetime import datetime
print("Hello please Enter Your Information")
First_Name = input("Enter Your First Name:-")
Second_Name=input("Enter Your Second Name:-")
Third_Name=input("Enter Your Third Name:-")
Id_Number=int(input("Enter Your Id Number:-"))
Address=input("Enter Your Address:-")
Pin_Code=int(input("Enter your Pin Code:-"))
Birthday = input("Enter your date of birth DDMMYYY:- ")
Bday = datetime.strptime(birthday, '%d/%m/%Y')
Gender=input("Enter Your Gender M/F:-")

print("---------------------------------------------------------------------------------")

print("Your Full Name:-",First_Name,Second_Name,Third_Name)
print("Your Id Number",Id_Number)
print("Your Address:-",Address)
print("Your Pin Code:-",Pin_Code)
print("Your Birthday:-",Bday)
if Gender== "M":
   print("Male")
else:
   Gender== "F"
   print("Female")
