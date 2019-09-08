#stone paper scissor game
import random
print("Welcome to Game \n")
print("Stone Paper Scissor \n")
i=1
user=0
cpu=0
str=["stone","paper","scissor"]
def winner(a,b):
    global user
    global cpu
    if(a=="s"):
        if(b=="paper"):
            cpu+=1
            return 0
        elif(b=="stone"):
            return 2
        else:
            user+=1
            return 1
    if (a == "p"):
        if (b == "scissor"):
            cpu += 1
            return 0
        elif (b == "stone"):
            return 2
        else:
            user += 1
            return 1
    if (a == "c"):
        if (b == "stone"):
            cpu += 1
            return 0
        elif (b == "stone"):
            return 2
        else:
            user += 1
            return 1
while(True):
    print(f"round {i} :")
    c=input("Enter your choice: s for stone || p for paper || c for scissor \n")
    c2=random.choice(str)
    print("Computers's choice = ",c2)
    n=winner(c,c2)
    if(n==1):
        print("you win")
    elif(n==2):
        print("Draw")
    else:
        print("you lose")
    choice=input("Do you want to play again? y/n \n")
    if(choice == "n"):
        print("Game Over")
        print(f"Total times game played = {i} times")
        print(f"You won : {user} times")
        print(f"Cpu won : {cpu} times")
        break;
    i += 1
