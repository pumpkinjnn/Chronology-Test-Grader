# Chronology-Test-Grader
This is the auto-grader for the chronology test for professor Silva's history class. This program will find the longest series of events in order by removing whatever event that is necessary. The result Grade will you give you the length of these events, and the correct sequence will display what those events are (only one possibility out of many).

## Open and Use
Download the .jar file and double click

or

Download the folder and everything inside it, open folder and keep everything in their relative space, double click on GradeVisualizer.class, this should be fine on Mac OS, will test on windows later. 

## A UI Demo
![alt text](https://github.com/pumpkinjnn/Chronology-Test-Grader/blob/master/Screen%20Shot%202019-03-16%20at%206.20.13%20AM.png)


Although the rough instruction is poseted inside the program, here is a detailed one.

## A user has two ways to use this Grader!

### 1. The events on the standard answer sheet and quiz sheet are in the same order.
In this case, simply type the numbers of the events, from top to bottom and seperated by space.

### 2. The events on the standard answer sheet and quiz sheet are not in the same order.
In this case, you need to make sure that the same position on the inputs means the same
event, for example, if you have standard answer sheet(left) and student quiz sheet(right):
```
Num   |     Event                                 Num  |   Event
 1    |    eating                                  2   |   exercising
 2    |    sleeping             -----\\            5   |   doing homework
 3    |    doing homework       -----//            4   |   eating
 4    |    playing game                            1   |   sleeping
 5    |    exercising                              3   |   playing game
 ```
 What you want to do is to enter students answer according to the sequence of the event on the standard
 answer sheet and its corresponding number in student's quiz sheet. Using the example above,
 first eating correspond to 4 in student's answer, so we put 4 first. Then sleeping is 1, doing homework 
 is 5, playing game is 3 and exercising is 2. Our input for the student's answer should then be like
 "4 1 5 3 2", and for the standard answer, simply "1 2 3 4 5."
 
 If this program breaks, please send a note to jinannan@grinnell.edu.
