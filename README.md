# yasaswi78
a=(input("enter a:"))
b=(input("enter b:"))
c=a+b
d=a-b
e=a*b
f=a/b
g=a%b
print("choose the choice:")
print("1.addition")
print("2.substration")
print("3.multiplication")
print("4.division")
print("5.modulo")
choice=int(input("enter your choice:"))
if choice==1:
    print(a,"+",b,"=",c)
elif choice==2:
    print(a,"-",b,"=",d)
elif choice==3:
    print(a,"*",b,"=",e)
elif choice==4:
    print(a,"/",b,"=",f)
elif choice==5:
    print(a,"%",b,"=",g)
else:
    print("enter the choice that had been provided!")
    
