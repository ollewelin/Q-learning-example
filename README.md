# Q-learning-example
Q-learning example
I good and clean tutorial by:
Aneek Das
https://towardsdatascience.com/introduction-to-q-learning-88d1c4f2b49c

I was change the last column transition_matrix from 1..4 to 0..3 

transition_matrix = np.array([[-1, 2, -1, 1, 0],
			      [-1, 3, 0, -1, 1],
			      [0, -1, -1, 3, 2],
			      [1, -1, 2, -1, 3]])
