from random import randint
t = ["rock","paper","scissors"]
computer =t[randint(0,2)]
player = False
while player==False:
    player=input('''what do you like to pick: 
                 * rock 
                 * paper
                 * scissors
                 ''')
                 
    player=player.lower()
    if player==computer: 
        print("Tie! both choose same thing")
    elif player=="rock":
        if computer=="paper":
            print("you lose",computer,"covers",player)
        else:
            print("you win",player,"smashes",computer)
    elif player=="paper":
        if computer=="scissors":
            print("you lose!",computer,"cut",player)
        else:
            print("you win",player,"covers",computer)
    elif player=="scissors":
        if computer=="rock":
            print("you lose..",computer,"smashes",player)
        else:
          print("you win",player,"cut",computer)
