m = "Hello my Name is Pravin"
print (m)                                          #printing the content of string m

# length function
#finding the length of the the String

print (len(m))                                     #printing the length of the string (m)

# index
#Accessing the items in the String with the index 

print (m[:])                                       #start with index 0 & goes untill end of String
print (m[:5])                                      #start with index 0 & goes untill index 4 & not including index 5
print (m[5:])                                      #start with index 5 & goes untill end of String
print (m[0:5])                                     #start with index 0 & goes untill index 4 & not including index 5
print (m[4:10])                                    #start with index 4 & goes untill index 9 & not including index 10
print(m[ : : 2])

# lower & upper case
#converting the string in upper and lower case

print (m.lower())                                  #Converting the string into lowercase
print (m.upper())                                  #Converting the string into uppercase

#count & find

print (m.count('i'))                               #counting the number of "i"  present in the string
print (m.find('Pravin'))                           #finding the "Pravin" in the string

#replace

nm = m.replace('Pravin','MAVERICK')                #replacing the "Pravin" with "MAVERICK" in the string
print (m)  #printing thre old string (m)
print (nm) #printing the new string  (nm)

#########

fname = "Pravin"                                  #Assigning value to the fname
lname = "Singh"                                   #Assigning value to the fname
name = fname + ' ' + lname   #adding two strings i.e [fame  & lname]
print (name) 
nname = "{} {}".format(fname, lname)
print (nname)

# F String Method

nname = f"{fname} {lname}"                         #f string method of adding strings
print (nname)
nname = f"{fname.upper()} {lname.upper()}"         #changing the string into uppercase & lowercase
print (nname)

#dir

print (dir(name))

#help

print(help(str))                                    #help function
print(help(str.count))

#NUMERIC
# 3 = int value
#3.123 = float value

num1 = 3 
num2 = 2.0
print (type(num1))                                  #printing  what types of value does num1 have
print (type (num2))                                 #printing  what types of value does num2 have

# Arithmetic operator

add = num1 + num2                              #Addition
sub = num1 - num2                              #Substraction
mult = num1 * num2                             #Multiplication
div = num1 / num2                              #Division
fdiv = num1 // num2                            #Floor division
exp = num1 ** num2                             #Exponent
mod = num1 % num2                              #Modulus

#"\n" for new line

print ( "Addition = ",add,"\n"
        "Subtraction = ",sub, "\n"
        "Multipliction = ",mult,"\n"
        "Divison = ",div,"\n"
        "Floor Division = ",fdiv,"\n"
        "Exponent = ",exp,"\n"
        "Modulus = ",mod,"\n")       #printing the arithmetic opernations

#increment  & decrement

num1 = num1 + 1   #increasing the value of num1 by 1
num1 -= 1                  #decresing the value of num1 by 1
num2 += 1                #increaing the value of num2 by 1
num2 *= 5                  #increaing the value of num2 by 5 times the value of num2

print (num1, "\n",
       num2, "\n")

# Absolute

print(abs(-5))   #printing the absolute value

#Round

print (round(3.75))          #round the value to it's nearest number
print (round(3.75, 1))      #round the value to it's nearest number by 1 decimal digit
print (round(2.12))

#comparison

num1 = 5
num2 = 9

#  "=" is used to assign the value & "=="  is used to compare the value

Equal = num1 == num2        #checking num1 value is Equal to Num2 value or not
Not_Equal = num1 != num2  # [(num1! = num2)means num1 is not equal to num2, ! represnt not ]
Greater_than = num1 > num2  #checkingnum1 value is greater than num2 value or not
Less_than = num1 < num2        #checking num1 value is less than num2 value or not
Greater_or_Equal = num1 >= num2  #checking num1 value is Greater or Equal  than num2 value or not
Less_or_Equal = num1 <= num2         #checkaring num1 value is Less or Equal than num2 value or not


print ("Equal = ",Equal, "\n" "Not Equal = ", Not_Equal, "\n"
       "Greater Than = ",Greater_than, "\n"
       "Less Than = ",Less_than, "\n"
       "Greater or Equal = ",Greater_or_Equal,"\n"
       "Less or Equal = ",Less_or_Equal,"\n")      #printing the comparision result

# string

num1 = "100"
num2 = "500"

print (num1 + num2)  #adding two stings 

#casting

num_1 = int(num1)  #converting the string value into integer value
num_2 = int(num2)
num_3 = float(num1)   #converting the string value into float value
num_4 = float(num2)

print(num_1 + num_2)  #adding two strings after casting

print ("Integer : ", num_1 + num_2 , "\n"
       "Float : ", num_3 + num_4)    

# lists, tuples & sets

c = ['Chemistry', 'Physics', 'Maths', 'Computer Science', 'Arts','Commerce']  # lists are enclosed in  [ ]
print (c)

#length
print(len(c))

# access each value individually {slicing]

print (c[0])                 #index value of 0th element
print (c[3])                #index value of 3rd element
print (c[-1])              #-1 index represent the last element of the lists
print (c[0 : 2])         #accessing element between the index value  [0:2] , here element of index 2 will not be prented
print (c[0:])              #accessing  element from index [0 : ] , here  after [:  ] if no index is input it will print the whole lists
print (c[:3])              #accessing the element from starting of list till the index 3 but not including the value of index 3
print (c[:])                # accessing the whole lists
print (c[: : 2])          #accessing the whole lists with the interval of 2 lists

# add an item to list

c1 = ['English', 'Biology']    #adding the elements in the lists
c2 = c1 + c                                 # adding the new element at the starting of list
print (c2)

c3 = c + c1                                # adding the new element at the end of lists
print (c3)

c.append('History')             #append method  to add the elements in lists (note - append() takes exactly one argument)
print (c)


# adding to specific location

c.insert(0,'Geography')     #insert method is used to add element  to a specific location in the list  (note - insert takes 2 arguments 1st argument is the index where you what to add the 2nd argument)
print (c)

#Extending
c1 = ['English', 'Biology']    # extend method is used to add the elements in the end of the list
c.extend(c1)
print (c)

#remove items

c.remove('Maths')         #remove function is used to remove the element  (Note - remove() takes exactly one argument )
print (c)

# removing last value    #pop function is used to pop(remove) out the element with the index & also pop out the last elemnt without it's argument

c.pop()            #direct  poping out element without storing it in variable
print (c)

#getting poped element
p = c.pop()     #Here p is the variable which will store the poped out element
print (p)          #poped element
print(c)           # list after poped value

z = c.pop(3)    #poping out elements with the index value  (Note - pop accept at most 1 argument)
print (z)          
print(c)


#reverse

c.reverse()    #inverting the list
print (c)

#sorting  Note = sort() takes no positional arguments

c.sort()         # sorting the list elemnts in alphabetic/accending order
print (c)
n = [10, 3, 3, 1, 6, 4, 1, 0, 7]
print(n)
n.sort()      # sorting the list elemnts in accending order (Note = here the original list will be sorted )
print (n)

#sorting without changing list

s = sorted(c)  #soting the list without changing the original list & storing the sorted list in the variable  s

#sorting in decending order


n.sort()               #sorting
n.reverse()       #sorting in decending order

n.sort(reverse = True)      #sorting in decending order
print (n)


#min max sum

print (min(n))       #finding minimum  value
print (max(n))      #finding maximum value
print (sum(n))      #finding  sum of all values

# finding index of certain value

print (c.index('Geography'))      #finding the index of an elements present in list

# checking value True Or False

print ('History' in c)           #checking the  elements present in the list and getting the the value as true or false
print ('ScienceS' in c)

#loop in list 

for i in c:          #looping in list will print the each value of list in new line
    print (i)

#printing index with lists

for index, i in enumerate(c):     #printing list in loop with the index no.
    print (index, i)

#stsrting with index 1

for index, i in enumerate(c, start=1):    #printing list in loop with the customized index no.
    print (index, i)

#converting list into string  & string in list
print(c)
s = ', '.join(c)           #converting list into string with the join method
print (s)

l = s.split(' , ')          #converting string into list with the split method
print (l)

s = ' - '.join(c)
print (s)

l = s.split(' - ')
print (l)
