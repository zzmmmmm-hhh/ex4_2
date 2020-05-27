# ex4_2


Zhuomin Zhou 519370910178

This program is used to take a sorted integer vector and an integer number from the command line, and output the location (index) of this integer using binary search.

The user should first follow the input command to input a sorted vector and an integer contained in the vector. Then, the program will output the index of the integer in the vector.

To realize the function,
We first take the vector and the integer by the input function. 
Then we take assign the smallest valus and greatest value to low and high. 
And we first take mean as the median number of vector and use ceil to make it an integer.
Then we use the while loop to compare the integer with every mean number. 
If integer is greater than mean, we take the low as mean+1 and compare mean to integer again. 
If interger is smaller than mean, we take the high as mean-1. 
And we if coincide with high then the value of mean should be the same as low .
Therefore, we can find the integer by the binary search and the index of integer will only be displayed when integer equals to mean.



