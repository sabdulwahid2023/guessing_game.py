# guessing_game.py

import random 
#guess = ()
workingValue = random.randint(1,100) 
guess = int(input("Give me a number "))
working = 0
#print(workingValue)
while True: 
    guess =int( input("Enter a number between 1 and 100:  "))
    if guess < workingValue: 
        print ("Your guess was too low. ")
        
    if guess > workingValue:
        print ("Your guess was to high. ")
        
    if guess == workingValue: 
        print (f"You have guess the correct number !!")
        break 
