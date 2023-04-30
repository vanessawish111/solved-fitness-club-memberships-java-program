Download Link: https://assignmentchef.com/product/solved-fitness-club-memberships-java-program
<br>
Consider a text file named memberships.txt that contains data relating to Fitness Club memberships. Each line within the file contains the following data items:

• first name (a string)

• surname (a string)

• age (an integer)

• membership type (a string, possible values are gym or circuit)

• weight in kilograms (a float)

• membership fee paid (a float),

Each data item is separated in the file by a space character. Hence, the data file contains data like the following:

Justin Time 23 gym 75.2 59.95

Eileen Over 21 circuit 45.7 59.95

Bob Down 19 circuit 89.1 160.50

Laura Norder 22 gym 65.5 120.00

make a Java program that uses the memberships.txt file as an input file and that performs the following tasks:

• creates an on-screen report which shows the total number of gym and total number of circuit members and their respective average membership fee;

• creates a text file named gym.txt that contains first name, surname, and membership fee for all members that have a gym membership. Hence, if the above example file was the input file the following would be the data in the gym.txt output file:

Justin Time 59.95

Laura Norder 120.00

• creates a text file named circuit.txt that contains first name, surname, and membership fee for all members that have a circuit membership.

Hence, if the above example file was the input file the following would be the data in the circuit.txt output file:

Eileen Over 59.95

Bob Down 160.50

An example members.txt file has been provided in the zip for this weeks exercises. Use this example input file to test your code. Make sure that your Java solution checks that the file exists before attempting to read from it. If the

file does not exist then handle this situation by informing the user that the file does not exist and then obtain a new file name/location from the user. You should also ensure that your code works correctly for different length files (ie,

the input files used for marking your program may contain more or less lines of text than the example file provided)