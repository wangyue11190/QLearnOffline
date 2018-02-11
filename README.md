# QLearnOffline
this is a qlearn pratice for the game of nine point game
the game board goes like this:
------
c1 c2 c3

0  0  0  (row 0)

0  0  0  (row 1)

0  0  0  (row 2)

so the points are as follows: (0,0),(0,1),(0,2) (1,0),(1,1),(1,2) (2,0),(2,1),(2,2)
------
two players play, one is 1 the other 2.
any side who can get his point a line no matter in a row, in a column or in a oblique line wins.like belows.
-----
1 1 1  

0 0 0  

0 0 0 

----- 
-----
1 0 0 	

1 0 0 	
 
1 0 0
 	
-----
-----
1 0 0

0 1 0

0 0 1

-----

so this is an example of using Reforcemant Learn to give a try to do the game. here we use  qlearn. the offline part is to do the training of 
qmatrix.

there are two steps: 1. cd pymain && python qlearn_status.py
					 2. cd pymain && python qlearn_core.py
