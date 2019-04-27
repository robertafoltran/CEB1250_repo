## method: print if a number is odd or even in python
def name():
    number = int(input("Enter a number: "))
    if (number % 2 == 0):
        print("This is an even number")
    else:
        print("This is an odd number")

name()



# Write a method that takes a number and print its square
def sqr(x):
    y=x**2
    print(y)

sqr(4)



# Write a method to convert degrees from Fahrenheit to Celsius.

def f2c(far):
    cel = (far-32)*(5/9)
    print(cel)

f2c(90)

# Method: return the largest number of a list

def largest_number(number_list):
    sorted_numbers = sorted(number_list)
    return sorted_numbers[-1]

    x = largest_number([1,5,9,7,10,87,0])
    print(x)


# Method: decide if a word is a palindrome
def pali(): 
    s = (input("Enter a string: "))
    str = "" 
    for i in s: 
        str = i + str
 
    if (s == str):
        print("This is a palindrome")
    else:
        print("This is NOT a palindrome")

pali()


# Create a method that returns the number of vowels per string.
def vow(x):
    vowels=0
    for i in x:
        if(i=='a' or i=='e' or i=='i' or i=='o' or i=='u' or i=='A' or i=='E' or i=='I' or i=='O' or i=='U'):
            vowels=vowels+1

    print(vowels)

vow("Pindamonhangaba")
