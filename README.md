# capstone-project
## **Plot and Navigate a Virtual Maze**

### **Overview:**
This project is based off the micromouse competitions and is, in fact, a virtual version of it, wherein a virtual robot mouse is placed in an unknown maze and firstly tries to map out the maze to figure out the optimal path from a corner of maze to its center. In the 2nd run, the virtual robot mouse attempts to reach the center in the fastest time possible by using what it has learned. 


### **Requirement:**

Python 2.7

IPython Notebook

numpy

Turtle (for drawing a graphical representation of a maze)


### **Display a graphical representation of a maze:**
\$ python tester.py test_maze_01.txt\


### **Run the robot through a maze:**
'$ python tester.py test_maze_01.txt'

### **Or if run the code in IPython Notebook:** 
change the code in line 28 of tester.py 
'testmaze = Maze( str(sys.argv[1]) )' 
to 
'testmaze = Maze('file name for a test maze')'. 
'file name for a test maze' can be 'test_maze_01.txt', 'test_maze_02.txt' and so on.


### **Batch run the robot through the randomly generated maze:**
$ python batch_maze_runner.py


### **Files included:**
1. capstone proposal document named proposal.pdf
2. project report named Project Report - Plot and Navigate a Virtual Maze.pdf
3. robot.py: the main code developed to include navigation logic
4. showmazed.py: the code provided by the project creator to display a graphical representation of a mazeprovided.
5. maze.py: the code provided by the project creator to get maze info from .txt file.
6. tester.py: the code provided by the project creator to execute the navigation
7. batch_maze_runner.py: the code modified based on Edward Minnett's code to run the tester.py for batch of mazes
8. Four test maze .txt files: three are provided and one is created for Free-Form Visualization.
9. A folder named generated_mazes: includes 157 mazes of 5 different sizes, results for each maze and Statistical Analysis in excel file.
10. A folder named Images: includes visualization for all mazes, initial solutions, final solutions and optimal paths. 
