# CompSci1

An alternate method of storing a string is to store each letter of the string in a single node of a linked list,
with the first node of the list storing the first letter of the string. Using this method of storage, no null
character is needed since the next field of the node storing the last letter of the string would simply be a
null pointer.

This program reads the input from the attached input.txt file in the following format:
3
6
abcdef
4
1234
2
cm

When the chars “abcdef” are read, your program will construct a linked list as follows:
LinkedList:
  head -> a -> b -> c -> d -> e -> f

