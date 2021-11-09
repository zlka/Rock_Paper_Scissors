# Rock_Paper_Scissors

from random import radint

# option for moves
moves = ["rock", "paper", "scissors"]

# user options
while True:
    computer_moves = moves[randint(0,2)]
    player_moves = input(" rock, paper or scissors? Enter your move: ").lower()

    if player_moves == computer_moves:
        print(" You draw! ")

    elif player_moves == "rock":
        if computer_moves == "paper" :
            print ("You lose!", computer_moves, "beats", player_moves)
        else :
            print("You win!" , player_moves , "beats", computer_moves)

    elif player_moves == "paper" :
        if computer_moves == "scissors"
            print("You lose!", computer_moves, "beats", player_moves)
        else :
            print("You win!" , player_moves , "beats", computer_moves)

    elif player_moves == "scissors":
        if computer_moves == "rock"
            print ("You lose!", computer_moves, "beats", player_moves)
        else :
            print("You win!" , player_moves , "beats", computer_moves)

    else :
        answer = input("Do you want to continue the game? ").lower()
        if answer = "yes" : continue
        else : break
    print("The game has ended")
