# Distance-between-two-nearest-neighbours

Java Function to find 2 neighboring numbers with the smallest distance
This Java function takes an integer array as input and returns the index of the 1st number in the array whose neighboring numbers have the smallest distance to each other.

Prerequisites
Java JDK installed on the system.
How to Use
Clone or download the repository to your local machine.
Navigate to the directory containing the code files.
Open the terminal/command prompt and compile the distance.java file using the command javac distance.java.
Run the compiled file using the command java distance.
Enter the length of the array when prompted and then enter the elements of the array one by one.
The program will output the two neighboring numbers with the smallest distance and their respective indexes.
Function Details
Method Signature

public static int findNearestNeighbors(int[] arr)
Input
The function takes an integer array arr as input.
Output
The function returns an integer which represents the index of the 1st number whose neighboring numbers have the smallest distance in the array.
Method Description
The findNearestNeighbors method initializes two variables minDistance and minIndex to keep track of the minimum distance and its index between neighboring numbers in the array.

The method then iterates through the array comparing the distance between each neighboring pair of numbers. If the distance between the current pair is smaller than the current minimum distance, minDistance and minIndex are updated to reflect the new minimum distance and its index respectively.

Finally, the method returns the index of the number whose neighboring numbers have the smallest distance.

Example
Input:

Enter the length of the array: 5
Enter the elements of the array: 5 7 10 13 17
Output:

The two neighboring numbers with the smallest distance are 10 and 13
The indexes for these nearest numbers are: 2 and 3
