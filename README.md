<h1>Treasure Game Project</h1>

<h2>Demo</h2> https://appbrewery.github.io/python-day3-demo/

<h2>Description</h2>
The goal was to build a "Treasure Island" game. Using what i had learnt on 'control flow and logical operators'. Its a simple version of text game.
<br />

<h2>Languages and Utilities Used</h2>

- <b>python</b>
- <b>pycharmce</b>


<h2>Environments Used </h2>

- <b>IOS Bigsur</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Treasure_Island_: <br/>
<img src="https://www.imag-r.com/static/uploads/Screenshot_2025-03-30_at_23.27.023040__extra.png?random=%3F1743366658" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Final Game Image: <br/>
<img src="https://www.imag-r.com/images/display/Screenshot_2025-03-30_at_23.28.063431__extra.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h2>Code</h2>
print("Welcome to Treasure Island.")
print("Your mission is to find the treasure.")
choice1 = input('you are at a T junction and have to type to choose to turn "left" or turn "right".'
      'which turn will you make? ').lower()
if choice1  == "left":
    choice2 = input("You have reached the beach, do you swim to the Island or wait for a boat?"
                    "Type 'Wait' or 'Swim'. ").lower()
    if choice2 == 'Wait'.lower():
        choice3 = input("You have reached a castle on the Island."
                        "choose a door by typing the color.'Red','Yellow' or 'blue'. ").lower()
        if choice3 == 'Red'.lower():
            print("Burned by fire.Game Over.")
        elif choice3 == 'Yellow'.lower():
            print('You just won the Lotto!!')
        elif choice3 == 'Blue'.lower():
            print('You\'ve got eaten by beasts.Game Over.')
        else:
            print("You have chosen a door that doesn't exist.Game Over")

    else:
        print("You got eaten by a crocodile. Game Over!!")

else:
        print("they fall in a pit full of snakes. Game over")

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
