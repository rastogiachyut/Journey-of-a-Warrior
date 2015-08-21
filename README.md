# Journey-of-a-Warrior

It is a game created using pygame library of Python

It is a game in which I have used several algorithms. This game consists of four levels; each level is based on a riddle which needs to be solved by the player to advance to the next level

GROUP MEMBERS:
•	Apurva Sahay (apoorv09s)
•	Shubham Rastogi (shubhamr20)
•	Achyut Rastogi (rastogiachyut)

Dijkstra’s Algorithm:
Space Complexity:  O(n2)
Time Complexity: O(n2)

Where n is the number of vertices.

Justification:
This algorithm has been used in the first stage which involves a riddle in which our hero has to reach from city A to I using the shortest possible path between the two cities. The map includes nine cities connected to each other to various paths each having some distance value generated using random function. The shortest path is calculated and stored and if the player calculates it correctly then he/she advances to next level otherwise the player will lose the game.

Cycle Sort:
Space Complexity:  O(n)
Time Complexity: O(n2)

Where n is the number of elements.

Cycle sort is an in-place comparison sort that is theoretically optimal in terms of the total number of writes to the original array, unlike any other in-place sorting algorithm. It is based on the idea that the permutation to be sorted can be factored into cycles, which can individually be rotated to give a sorted result. It also calculates the minimum number of moves required to sort the array elements.

Justification:
In the second stage we have used the Cycle Sort to calculate the minimum number of moves required to sort the floating stones in the ascending order from bottom to top to form the path for the hero to cross the valley and advance to the next level. If the player sorts the stones in minimum number of moves they advance to the next level.

Typewriter Algorithm:
Space Complexity:  O(n)
Time Complexity: O(n)

There is a class with three functions. The first function initializes the variables speed and string with zero and Null respectively. The third function updates the string to its full length if the user clicks. The second function is the main function  which appends the new character to the already existing string every time the function call value becomes equal to the speed value.

Justification:
This is more of a kind of technique than an algorithm which we have used to generate a typewriter effect while displaying conversation between the hero and the old man. In this we increase the length of the string to be displayed after equal intervals so when the string is drawn on the canvas, each time there is new character along with the old ones so that it seems as if the story is being written on the screen using a typewriter.

Food Rationing Problem:
Space Complexity: O(n)
Time Complexity: O(n)

Here n is the number of sacks (elements in the array).

def angry_c(a, n, k):
  a – Array of sacks.
  n – Number of Sacks
  k – Number of Houses
    k=k-1;
    a.sort(); # sort the array is ascending order
    i=0;
    sm=a[n-1];
    while (i+k)<n:
        d=a[i+k]-a[i];
        if(d<sm):
            sm=d;
        i+=1
    return sm;

Justification:
This problem is based on the problem from Hackerrank. It involves the problem of distribution of sweet packets amongst angry children in such a way so that it minimizes unfairness. We have modified this problem and used it for angry villagers involving distribution of food sacks amongst villagers in a similar way. The details have been already specified in the game.

0/1 Knapsack:
Space Complexity: O(n2)
Time Complexity: O(n2)

Justification:
This algorithm has been used  for the last stage involving armoury selection. The player has limited inventory size and he/she has to select the weapons and armours in such a way so as to maximize attribute value for the hero subject to the limited size of the inventory. If the items have been chosen properly then the hero will be able to survive the final fight otherwise he fails.


SCREENSHOTS

============================================================================

![title](https://cloud.githubusercontent.com/assets/11174059/9405029/efcbf2ca-4811-11e5-8b9c-50e5cadeb178.jpg)
![final](https://cloud.githubusercontent.com/assets/11174059/9405032/effe56de-4811-11e5-887d-9e3fe9b2ea21.jpg)
![map](https://cloud.githubusercontent.com/assets/11174059/9405031/effbe458-4811-11e5-9320-7177f75d7698.jpg)
![stage2_2](https://cloud.githubusercontent.com/assets/11174059/9405030/effb61ea-4811-11e5-98b5-17c2f1d845ff.jpg)
![story](https://cloud.githubusercontent.com/assets/11174059/9405033/f00ce492-4811-11e5-90d4-2127dcebc425.jpg)


