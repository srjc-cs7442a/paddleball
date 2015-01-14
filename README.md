# paddleball
In class exercises:
1. Write a program that displays the phrase "Hello, World!" to the user.

2. Write a program that computes the sum of 5 + 10 and displays the result to the user.

3. Write a program that prompts the user to enter his or her name and then responds with "Hello, <insert name here>." For example, if the user entered "James" as his name, the program
will display the phrase "Hello, James."

4. Write a program that prompts the user to enter a number and then displays the number multiplied by itself. For example, if the user inputs "3" the program displays "9" (which is 3 x 3). (Hint: use the Number() function to convert the string value returned by prompt into a number value). 

5. Write a program that prompts the user to enter two numbers and then displays the sum of those two numbers. (Hint: use two separate prompt() calls to get the two numbers).

6. Write a program that displays the numbers 1, 2, 3, 4, 5 to the user via consecutive alert boxes. (The first alert box shows "1", after clicking okay, the second alert box shows "2", etc.)

7. Write a program that prompts the user to enter a number. If the number is evenly divisible by two, the program will display the text "Your number is evenly divisible by two!" If the the number is not evenly divisible by two, nothing is displayed.

8. Write a program that computes 11! and displays the result to the user. (Hint: 11! means "11 factorial"--google "factorial" if you are unfamiliar with this term.

9. Write a program that prompts the user to input three adjectives describing themselves and then displays a string to the user that uses all three adjectives. For example if the user enters "smart," "handsome," and "rich", the program could display "You are a smart, handsome, and rich person."

10. Write a program that prompts the user to enter a temperature in fahrenheit and the displays that temperature converted to celcius.

Complete these (11-21) as homework and bring them to next class:

11. A multiple-dial combination lock has three rings of numbers from 1 - 10. One setting of these three rings is the combination that opens the lock. Write a program that computes the number of possible combinations for such a lock and displays the number to the user.

12. Write a program that prompts the user to enter a number and then displays the absolute value of that number. For example, if the enters "5" the program will display "5." if the user enters "-5" the program will display "5." (Hint: the absolute value of a number is its distance from zero on the number line. -3 and 3 are both 3 units away from zero.)

13. Write a program that displays all numbers between 1 and 100 that are evenly divisible by 7. Display the numbers in a single alert. (Hint: use string concatonation to build the string you will display).

14. Write a program that prompts the user to enter two numbers and then displays whichever number is greater.

15. Write a program that computes 121 divided by 7 and displays the result of the division AND the remainder to the user. For this program, you are not allowed to use the / or % operators.

16. The original Nintendo Entertainment System (NES) had a screen resolution of 256 horizontal pixels by 240 vertical pixels. Write a program that calculates the numbers of 16 pixel x 16 pixel tiles that could fit within this space (without drawing past the edge of the screen). Display the calculated number of tiles to the user. 

17. Write a program that's a simple role-playing game character generator. This program will ask the player a few questions and then pick an appropriate character class (job or profession) based on the player's answers. Ask the player two questions: "Is your character strong?" and "Is your character smart?" Then pick the class based on these options:

strong, not smart: barbarian
not strong, smart: wizard
strong, smart: arcane warrior
not strong, not smart: peasant

display the chosen character class to the user. 

18. Write a program similar to the one in question 16 but choose your own questions and character classes. Be sure to cover all combinations that your questions allow--notice how quickly the number of possible combinatons grows... (Hint: each new question increases the number of classes by a power of two. One question = two classes, two questions = four classes, three questions = eight classes, four questions = 16 classes, etc.)

19. Write a program that determines whether the user should play baseball today. The program should contain three variables that reference boolean values representing whether it is currently raining, whether it is currently snowing, and whether the user has access to a covered stadium. (You do not need to prompt the user to answer questions, just assign true or false to these variables directly). If it is raining or snowing and the user does not have a covered stadium, advise the user that it is not a good day to play baseball. Otherwise, advise the user that it is okay to play baseball today. Experiment by setting the three variables to different boolean values and test how this affects the final output of your program.

20. Write a program that prompts the user repeatedly to answer the question "Do you want to quit?" The program will ask this question again and again until the user answers "yes," at which point the program will stop asking the question. (Hint: create a variable named "wantsToQuit" that initially contains the boolean value to false. Then create a while statement that uses this variable as the exit condition (i.e., while(!wantsToQuit)). Set wantsToQuit to true within the while loop if the user enters the appropriate text).

21. Write a program that will prompt the user to enter text and then displays what the user typed. For example, if the user typed "go north" the program would output "you typed: go north." The program will continue prompting the user for input and displaying what was typed until the user enters "quit." After the user enters "quit," the program will display the text "Thank you for playing." and then does nothing. 
