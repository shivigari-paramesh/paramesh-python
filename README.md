#division of two numbers by using global variable
'''global div
a=10
b=30
def calculate():
    sum=a+b
    div=sum/2
    print(type(sum),sum,int(div),type(div))
calculate()'''


'''global div
def calculate():
    sum=40
    div=sum/2
    print(type(sum),sum,int(div),type(div))
calculate()'''

'''print(a[:-5])
print(len(a))
print((a[::]))'''

a="masani ntk"
b="Naresh"
c="Kumar"
d="10"
e="WELCOME"
f=" "
'''print(a.capitalize())#first character returns capital
print(a.casefold())#casefold method returns lowercase

print(a.count("n"))
print(a.center(30))
print(a.encode())
print(a.endswith("m"))
print(a.endswith("kumar"))
print(a.endswith("Kumar"))
print(a.expandtabs())
print(a.find("K"))# it finds the position of the string
print(a.index("n"))
print(a.isalnum())
print(a.isalpha())
print(d.isdecimal())
print(d.isdigit())
print(d.isidentifier())
print(a.islower())
print(d.isnumeric())
print(d.isprintable())
print(f.isspace())
print(e.istitle())
print(e.isupper())
print(b.ljust(5,"@"))
print(b.lower())
print(a.lstrip())'''

'''for i in range(1,6):

    if i==3:
        continue
    print(i)


for i in range(1,6):

    if i==3:
        break
    print(i)


for i in range(1,6):
    print(i)
    if i==3:
        continue

for i in range(1,6):
    print(i)
    if i==3:
        break

b=["apple","banana","mango"]
for i in b:
    if i=="banana":
        continue
    print(i)

a=333
b=220
if a>b:
    print("a is greater")'''
'''if a>b:
    print("a is greater")
else:
    print("b is greater")'''
'''if a>b:
    print("a is greater than b")
elif a==b:
    print("a is equal to b")
else:
    print("a is less than b ")'''



class student:
    def student(a):
        if a.marks>=40:
            return "pass"
        else:
            return "fail"
st1=student()
st1.name="naresh"
st1.marks=90
print(st1.name)
print(st1.marks)

print(st1.student())
'''
def calculate():
    a=10
    b=20
    c=a+b
    print(c)
calculate()

x = lambda a,b,c:(a+b+c)**3
print(x(2,3,4)
class building:
    def coaching(self):
        if self.students==10:
            print("coaching is python")
        elif self.students==5:
            print("coaching is both cad and python")
        else:
            print("cad coaching")
room1=building()
room2=building()
room1.laptops=5
room1.students=5
room2.drawing="drawing table"
room2.students=10
print(room1.laptops)
print(room1.students)
print(room2.drawing)
print(room2.students)
print(room1.coaching())
class laptop:
    def laptop(self):
        if self.ram==4:
            return "its good"
        else:
            return "its bad"
laptop1=laptop()
laptop2=laptop()
laptop1.ram=4
laptop1.battery=4500
laptop2.ram=2
laptop2.battery=2000
print(laptop2.ram)
print(laptop1.laptop())
print(laptop2.laptop())'''
'''x=2
y=3.5
z=10j
a=float(x)
b=complex(z)
c=complex(y)
print(a)
print(b)
print(c)
print(type(a))
print(type(b))
print(type(c))
a="masani naresh"
b="Masani Naresh"
print(a.strip())
print(a.replace('a','i'))
print(a.split())
print(b.lower())
print(b[::])
print(b[:-1])
print(b[-1])
print(b[2:])

txt="the best things in life are free"
if "free" in txt:
    print("yes, 'free is present' ")
txt = "the best things in life are free"
if "expensive" not in txt:
    print("yes, 'expensive is not present' ")
txt="the best things in life are free"
print("free" in txt)
txt="the best things in life are free"
print("expensive" not in txt)
txt="the best things in life are free"
print("expensive" in txt)
a="masani"
b="naresh"
c=a+b
print(c)
x="hello"
y=0
print(bool(x))
print(bool(y))
x="naresh"
y="naresh"
print(x is y)
x="naresh"
y="masani"
print(x is y)
x="naresh"
y="naresh"
print(x is not y)
x="naresh"
y="masani"
print(x is not y)

#program on to add two numbers in python
a=10
b=20
c=a+b
print('addition of two numbers is ', c)
#program on to print the  maximum of two numbers
n1=int(input('enter a number 1'))
n2=int(input('enter a number 2'))
if n1>n2:
    print('the maximum number is', n1)
else:
    print('the maximum number is ', n2)
#using max function
n1=int(input('enter a number 1'))
n2=int(input('enter a number 2'))
x= max(n1,n2)
print(' Maximum number is', x)
#si=ptr/100 program on simple intrest
p=int(input('enter a principle amount'))
r=int(input('enter a rate of intrest'))
t=int(input('enter a time '))
si=p*t*r/100
print('the simple intrest of given data is ', (si))'''


list methods

'''These are all the list methods using in python'''

ssfrnd=["ani",  "par", "mah","mah"]
ddfrnd=["sri", "shy","ven"]
'''print(ssfrnd[1])
print(ssfrnd.index("mah"))  #Index method
ssfrnd.append("jag")        #append method
print(ssfrnd)
ssfrnd.extend(ddfrnd)       #extend method
print(ssfrnd)
ssfrnd.insert(2,"ravi")     #insert method
print(ssfrnd)
ddfrnd.remove("ven")        #remove method
print(ddfrnd)
numbers=[1,2,3,4,5,6,3,4,5,3,3,4,4,5,5,5,5]
n1=numbers.count(3)         #Count method
print(n1)
frnd=ssfrnd.count("mah")
print(frnd)
n1=[5,3,4,6,2,1,8]
frd=n1.pop(-1)              #pop method using slicing indexing
print(frd)
frd=n1.pop(4)               #pop method using normal indexing
print(frd)

n1= [5, 3, 4, 6, 2, 1, 8]
n=n1.copy()                 #copy method returns a copy in a list
print(n)
n=n1.clear()                #clear method-clears all the data in a list then gets empty list printed in print(n1)
print(n)
print(n1)
n=[2,4,3,1,6,5,8]
n.sort()                    #sort method - is used to sort or ascending to decending changes in a list
print(n)
n.reverse()                 #reverse method- it is used to reverse a data in a list
print(n)
'''

set methods


'''These are all the set methods using in python'''
'''
ssfrnd={"ani",  "par", "mah"}
ddfrnd={"sri", "shy","ven"}
ssfrnd.add("jag")           #add method is using to add a data in a set
print(ssfrnd)
ddfrnd.copy()               #copy method is used to copy all the data in a set
print(ddfrnd)
ddfrnd.clear()              #clear method is used to clear all the data in a set its shown set() is printed ina output
print(ddfrnd)
#n1=ddfrnd1.difference(ssfrnd)      # difference method is used to returns a set that removes in two or more set in a same name
#print(n1)
ssfrnd.difference_update(ddfrnd1)   #difference update is used to returns a set that same name removes in a set

print(ssfrnd)
ssfrnd.discard("mah")               # discard method is used to remove specific item in a set
print(ssfrnd)

ssfrnd={"ani",  "par", "mah"}
ddfrnd1={"sri", "par", "shy"}
n=ssfrnd.intersection(ddfrnd1)      #intersection method is used to returns an same name in  a two or more sets
print(n)

ssfrnd={"ani",  "par", "mah"}
ddfrnd1={"sri", "par", "shy"}
ssfrnd.intersection_update(ddfrnd1)      #intersection method is used to returns an same name in  a two or more sets
print(ssfrnd)

ssfrnd1={"raj","ram","ravi"}
ddfrnd2={"ravi","raj","ram"}
n=ssfrnd1.isdisjoint(ddfrnd2)           #isdisjoint set method- returns boolena value
print(n)
n=ssfrnd1.issubset(ddfrnd2)             # issubset method- returns boolean value
print(n)
n=ssfrnd1.issuperset(ddfrnd2)           #isuperset method-returns boolean value
print(n)

ssfrnd1={"raj","ram","ravi"}
ddfrnd2={"ravi","raj","ram"}
#ddfrnd2.pop()                              # pop method removes random item from the set
#print(ddfrnd2)
ssfrnd3={"raj","ram","ravi"}
ssfrnd3.remove("raj")                       #remove method removes a specific item 
print(ssfrnd3)

s1={"raj","ravi","ramesh"}
d1={"ram","rakesh","ravi"}
#f1=s1.symmetric_difference(d1)      #symmetric difference method used to remove a same name in two or more sets with new variable to print
#print(f1)

#s1.symmetric_difference_update(d1)    #symmetric difference method used to remove a same name in two or more sets without new variable to print
#print(s1)
#g1=s1.union(d1)                     #union method returns a set that containing a union of sets
#print(g1)
s2={"vis","mar","Vin","venky"}
d2={"ksh","bmrd","venky"}
s2.update(d2)                   #update method-update the set with another set or any other iterable repeats data prints only one time and updated
print(s2)'''

Tuple Methods

'''These are tuple methods in python'''

mytuple=(2,5,3,6,8,1,3,6,7,0)
print(mytuple)
print(mytuple.count(3))         #count method it counts the no of times present a value in a tuple ex 3 present 2 times in a tuple
print(mytuple.index(8))         # index method it retunrs a index of a given data in a tuple ex 8 given 8 index is 4 returns 4


Dictionary Method

'''These are Dictionaries methods in python '''
'''frnd={"name":"mah", "class":"ssc","year":2012}
my=0
#print(frnd)
#print(frnd.copy())      #copy method - copies all the data in a dictionary
print(frnd.clear())     #clear all the data return empty dictionary 
print(frnd)

mydic={"key1","key2","key3"}
edic={1,2,3}
k=dict.fromkeys(mydic,edic)     #fromkkeys method returns a dict with specified keys and value
print(k)

frnd1={"name":"mah", "class":"ssc","year":2012}         #get method returns specific key value
print(frnd1.get("year"))
print(frnd1.items())                            #items method returns all the data in a dictionary

dict=frnd1.keys()                           #keys methods returns keys in a dictionary
dict=frnd1.values()                     #values methods returns values in a dictionary
frnd1.update({"school":"GHS"})             #update method updates the data in a dictionary
print(frnd1)
frnd1.update({"name":"anil"})             #update method updates the data in a dictionary
print(frnd1)
frnd1={"name":"mah", "class":"ssc","year":2012}
dict=frnd1.setdefault("class","dip")            #default method returns the value of specified key
print(dict)
frnd1={"name":"mah", "class":"ssc","year":2012}
print(frnd1.popitem())                          #popitem method - Removes the last inserted key-value pair
print(frnd1)
frnd1={"name":"mah", "class":"ssc","year":2012}
frnd1.pop("name")                                #pop method- Removes the element with the specified key
print(frnd1)'''

##-----<>---programs on list----<>------##

''' # 1--->Python program to interchange first and last elements in a list

def swap():
    mylist=[10,23,87,65,35]
    temp=mylist[0]
    mylist[0]=mylist[-1]
    mylist[-1]=temp
    print(mylist)
swap()

# 2----> Python program to swap two elements in a list
def swapposition(list,pos1,pos2):
     list[pos1],list[pos2]=list[pos2],list[pos1]
     return list
list=[19,65,23,56]
pos1,pos2=0,2
print(swapposition(list,pos1,pos2))


#3---->Python | Ways to find length of list

list= [13,23,24,65,46,58,74,98]
n=len(list)
print("total length of the list is ", n)

#4--------->  Python | Ways to check if element exists in list
list=[1,2,4,6,7,4,5,8,9]
for i in list:
    if(i==4):
        print("element found or Element exists in a given list")
        break

#5------>Different ways to clear a list in Python
#1------>
list=[15,30,23,43,23,25,63]
clrlist=list.clear()
print(clrlist)
print(list)
#2-------->
list2=[21,23,43,15,64,75,36,74,37]
list2=[]
print(list2)

#6------> program on Reversing a List
list=[12,33,45,32,67,54,86,65]
#1--->print(list[::-1])    #------>using Slicing
#2--->list.reverse()        #-------> using reverse list method
print(list)
'''

'''#7-------> program to find the sum of elements in a list
list=[12,3,2,54,67,43,67,43]
total=0
for ele in list:
    total=total+ele
print('the total sum of the elements in a list is', total)
#8--------> multiply all the elements in a list
list1=[1,5,6,2]
mul=1
for ele in list1:
    mul=mul*ele
print('the multiply of all elements in a list is',mul)
#9-------------->to find smallest number in a list using 1.sort 2. min methods
#1---->sort()
list=[45,32,65,23,98,3,12]
#list.sort()
#print('smallest number in a list is',list[:1])
#------>min
print('the smallest number in a list is', min(list))
#10-------------> To find the largest element in a list
list=[45,32,65,23,98,3,12]
#1-----> max method
print(max(list))
#2---------> sort method using slicing
list.sort()
print('the largest element in a list is',list[-1])

#11----------------> to find the second largest element in a list
#1--------------> sort
list=[45,32,65,23,98,3,12]
list.sort()
print('the second largest element in a list is ', list[-2])
#2-------> remove
list=[45,32,65,23,98,3,12]
new_list=set(list)
new_list.remove(max(list))
print('the second largest element in a list is',max(new_list))'''
list=[45,32,65,23,98,3,12]

12------------> to find n largest elements in a list
list=[235,34,239,89,376,96,87]
n=int(input('enter a number'))
list.sort()
print('the largest elements in a list is:',list[-n:])

#13------> to print even numbers in a list
list1=[235,34,239,89,376,96,87]
for i in list1:
    if i%2==0:
        print(i)


#14----------> to print odd numbers in a list
list1=[235,34,239,89,376,96,87]
for i in list1:
    if i%2==1:
        print(i, end=" ")
#15------> to print all even numbers in a range
a=int(input('enter a number'))
b=int(input('enter a number'))
for num in range(a,b+1):
    if num%2==0:
        print(num, end=" ")

#16--------> to print all odd numbers in a range

a=int(input('enter a number'))
b=int(input('enter a number'))
for num in range(a,b+1):
    if num%2==1:
        print(num, end=" ")
#chech whether a number is prime or nor

n=int(input('enter a number'))

if n>1:
    for i in range(2,int(n/2)+1):
        if n%i==0:
            print(n,'is not a prime number')
            break
    else:
        print(n,'num is prime number')
else:
    print(n,'num is not prime number')
#17------------>Print all positive numbers in a given list

list1=[-25,34,-19,89,-6,96,-9]
for i in list1:
    if i>0:
        print(i)
#18------------> print all negative numbers in a given list
list1=[-25,34,-19,89,-6,96,-9]
for i in list1:
    if i<0:
        print(i)
#19 -------> remove multiple elements in a list
list1=[-25,34,-19,89,-6,96,-9]
del list1[1:5]
print(list1)'''


# To print a pyramid pattern

rows = int(input("Enter the number of rows:"))
k = (2 * rows) - 2  # It is used for number of spaces
for i in range(0, rows):
    for j in range(0, k):
        print(end="#")
    k = k - 1   # decrement k value after each iteration
    for j in range(0, i + 1):
        print("* ", end="")  # printing star
    print("")
    
    #snake game some changes to be done
    
    
    '''
name=input('Enter a name ')
#print('enter a name is :',name)
#print(name[::-1])
originalName=name
print('originalName is',originalName)
reversedName=""
for i in name:
    reversedName=i+reversedName
print('reversed name  {} is {}'.format(name,reversedName))
if reversedName==originalName:
    print('yes')
else:
    print('no')
'''
# method to remove i'th character using replace()
import random
import time

'''
name = input('enter a name')
print ("The original string is : " + name) #printing OriginalName
newName = name.replace('e', '')             #replace a string
print ("The string after removal of e character: " + newName)
newName = name.replace('s', '', 1)
print ("The string after removal of only once by using 1  : " + newName)
'''
'''
#----------> Check if a substring is present in a given string
def naresh(mystring,substring):

    if (mystring.find(substring)==-1):
        print("yes")
    else:
        print("no")
mystring="masani"
substring="masani naresh"
naresh(mystring,substring)
