So basically,this project is about evaluating OMR sheet. Here all the unevaluated but attempted OMR sheets are 
scanned beforehand in the computer. Then according to the student name (can be done with roll number also) and 
subjects,they are saved. For every OMR sheet there is an answer key (we've stored the correct answer in a dictionary 
corresponding to the key as question and value as the correct answer).For evaluation part, the evaluator has to type 
in the name of the student and choose the OMR correspondingly. Then the program will evaluate the OMR showing each 
OMR with correct answer bubbled as green and incorrect answers as red. Then it will calculate the total correct 
answers and give the percentage analysis of each subject in a pie chart.Then it will store the name of student along 
with his/her subject wise score as well as the total score in a text file called data.txt.

To set up with the project you need to install the following modules using the pip install command in the command prompt/anaconda prompt:-
-> open cv
-> imutils
-> tkinter
-> plotly
-> numpy
-> matplotlib
