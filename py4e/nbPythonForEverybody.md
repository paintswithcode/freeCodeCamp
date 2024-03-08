# Legacy Python for Everybody
Python is one of the most popular, flexible programming languages today. You can use it for everything from basic scripting to machine learning.

## Python for Everybody description
>Python for everybody is a free video course series that teaches the basics of using Python 3.

>The courses were created by Dr. Charles Severance (also known as Dr. Chuck). He is a Clinical Professor at the University of Michigan School of Information, where he teaches various technology-oriented courses including programming, database design, and web development.


## Python for Everybody curriculum
0/56, 0 of 56 challenges completed
Not Passed
### 01 Introduction: Why Program?
[Course source link: lessons, resources, etc - PY4E.com](https://www.py4e.com/)
Course is maintained by instructor Charles R. Severance and based on eponymous book *Python for Everybody: Exploring Data in Python 3*.

* Data, information and networks are our problems to solve when we develop software on behalf of the users, who want to do something without taking the time and energy to figure out how.

[  ] install Python -- and IDE Options:
* Local installation (python.org)
	* Win: As you install Python, make sure to check the "Add Python 3.5 to PATH" so that you can type **python** at the command line prompt to run it.
	* Have a text editor ([Brackets](https://brackets.io/), etc.)
	* You can also set up Python under Windows-10 using the Windows Subsystem for Linux (WSL) if you prefer a Linux-like experience on your windows computer.
* Cloud / browser based - no installation required
	-   [Replit.com](https://replit.com/@ChuckSeverance/PY4E?v=1#main.py) -- Use this course template to get a jump start -- Pricing bumps up to $20/mo.
	-   [PythonAnywhere](https://www.pythonanywhere.com/) -- They have a free level that will cover all of your needs for this course through Chapter 15 -- Pricing bumps up to $5..12/mo.
	- Other cloud-provided Python environments include [Trinket](http://trinket.io/), [Cloud9](http://c9.io/), or [CodeAnywhere](http://codeanywhere.com/).
* Both cloud options utilize Linux Shell, so get comfortable with Bash commands
* [According to Geeks4Geeks, the best Python IDE](https://www.geeksforgeeks.org/top-10-python-ide-and-code-editors-in-2020/)s are:
	1. [PyCharm](https://www.jetbrains.com/pycharm/) -- **(POP)** $99/yr.
	2. [Spyder](https://www.spyder-ide.org/) -- **(FAV)** a free and open source scientific environment (coding IDE + visualization capabilities) mainly used by data scientists who can integrate with [Matplotlib](https://www.geeksforgeeks.org/matplotlib-tutorial/), SciPy, [NumPy](https://www.geeksforgeeks.org/python-numpy/), [Pandas](https://www.geeksforgeeks.org/pandas-tutorial/), Cython, IPython, SymPy, et al. Install via Anaconda Navigator distribution system. Tour Spyder on [Binder](https://mybinder.org/v2/gh/spyder-ide/binder-environments/spyder-stable?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Fspyder-ide%252FSpyder-Workshop%26urlpath%3Ddesktop%252F%26branch%3Dmaster).
	3. [PyDev](https://marketplace.eclipse.org/content/pydev-python-ide-eclipse) -- Eclipse plug-in written in Java, but you can use it for Python as well. Assumes that you have already have **Python and/or Jython and/or IronPython** installed in your machine, as well as **Eclipse** (an open source IDE).
	4. [IDLE](https://docs.python.org/3/library/idle.html) -- free(?)
	5. [Wing](https://wingware.com/) -- **(FAV)** freemium; $245 perpetual license

#### Running a program from the <abbr title="command line interface">CLI</abbr>
Type "python" in Win CLI to open python CLI. To run a program:

	python firstprog.py

or

    firstprog.py

### 02 Introduction: Hardware Architecture
* CPU = microprocessor (MPU) = brains, fast, seeking instructions
* Memory stick (RAM) = very fast memory, lost when power 0
	*Software runs on CPU + RAM
	* CPU runs hot because so fast.
	* Microprocessors are essentially same architecture as CPU, but all the capacitors, resistors, transistors are micro-rendered 3D using photographic printing technology.

### 03 Introduction: Python as a Language

### 04 Introduction: Elements of Python

### 05 Variables, Expressions, and Statements
Python is case-sensitive. Name your variables accordingly. Avoid case as a differentiator. Prefer to use underscores  instead of camelCase - pretty common.

Name well for remembering what a variable is for, rather than name length. However, don't mistakenly apply more intelligence to the system because of meaningful (to you) variable names.

### 06 Intermediate Expressions
* Integer division always produces a decimal result (Python 3).
* Power is ** so 2***3 = 8
* Remainder (mod) % so 10 % 3 = 1

Python command formats:
*type(x)* will tell you type
*print(x)* will output
*float(x)* turns x from an int to a float
*input('Question?')* returns a string (the response)
*# comments* 
*handle = open(name, 'r')* opens a file (in read mode?)

### 07 Conditional Execution
* No tabs (to avoid indentation errors). Use spaces only. Make sure your text editor options are set for this re: Python files.
	* Indent convention: use 4 spaces
	* Editor: Settings > Prefs > Language Menu/Tabs
* If-then structure format <code><br/>if p: <br/>&nbsp;&nbsp;q</code>
* Indentation controls where you are in if statement, thus:  <code><br/>if p: <br/>&nbsp;&nbsp;q1<br/>&nbsp;&nbsp;q2<br/>&nbsp;&nbsp;q3<br/>else: <br/>&nbsp;&nbsp;e1</code>


### 08 More Conditional Structures
* elif is "else if" -- 
<code>
if p: q
elif p2: q2<br/>else p3 : q3
</code>

* Try/except structure -- 
<code>
try
&nbsp;&nbsp;varint = int(varnonint)
&nbsp;&nbsp;#can try multiple things
except
&nbsp;&nbsp;varint = catchint
&nbsp;&nbsp;quit() #exit clause for this script
</code>

For example:
<code>
rawstr = input('Enter a number: ')
try
&nbsp;&nbsp;ival= int(rawstr)
except
&nbsp;&nbsp;ival= -1
if ival > 0 :
&nbsp;&nbsp;print('Nice number!')
else
&nbsp;&nbsp;print('Not a number: ', rawstr)
</code>

* "Traceback (most recent call last): " is the runtime error log response.
* Print(var1, var2) will output "var1 var2" with the space between them.

### 09 Python Functions
Functions for storage and reuse -- 
#### Define and invoke:
<code>def thing() :
&nbsp;&nbsp;print('a')
&nbsp;&nbsp;print('b')
thing() # will print a and b
</code>

 - Def defines a function, and stores whatever is indented next as the function statement

- Call (invoke) the function using 
	- method call -- funk() 
	- or return value -- return(funk)
		- Return is the end of the function, specifying output
- Parameters funk(param)

#### Built-in functions

 - max('word') will return max alpha char, so "w"


### Build your own Functions

### Loops and Iterations
Passed
Syntax:
```python
n = 0
while True:
    if n == 3:
        break
    print(n)
    n = n + 1
```
### Iterations: Definite Loops
Not Passed
Iterations: Loop Idioms
Not Passed
Iterations: More Patterns
Not Passed
Strings in Python
Not Passed
Intermediate Strings
Not Passed
Reading Files
Not Passed
Files as a Sequence
Not Passed
Python Lists
Not Passed
Working with Lists
Not Passed
Strings and Lists
Not Passed
Python Dictionaries
Not Passed
Dictionaries: Common Applications
Not Passed
Dictionaries and Loops
Not Passed
The Tuples Collection
Not Passed
Comparing and Sorting Tuples
Not Passed
Regular Expressions
Not Passed
Regular Expressions: Matching and Extracting Data
Not Passed
Regular Expressions: Practical Applications
Not Passed
Networking with Python
Not Passed
Networking Protocol
Not Passed
Networking: Write a Web Browser
Not Passed
Networking: Text Processing
Not Passed
Networking: Using urllib in Python
Not Passed
Networking: Web Scraping with Python
Not Passed
Using Web Services
Not Passed
Web Services: XML
Not Passed
Web Services: XML Schema
Not Passed
Web Services: JSON
Not Passed
Web Services: Service Oriented Approach
Not Passed
Web Services: APIs
Not Passed
Web Services: API Rate Limiting and Security
Not Passed
Python Objects
Not Passed
Objects: A Sample Class
Not Passed
Object Lifecycle
Not Passed
Objects: Inheritance
Not Passed
Relational Databases and SQLite
Not Passed
Make a Relational Database
Not Passed
Relational Database Design
Not Passed
Representing Relationships in a Relational Database
Not Passed
Relational Databases: Relationship Building
Not Passed
Relational Databases: Join Operation
Not Passed
Relational Databases: Many-to-many Relationships
Not Passed
Visualizing Data with Python
Not Passed
Data Visualization: Page Rank
Not Passed
Data Visualization: Mailing Lists


> Written with [StackEdit](https://stackedit.io/).
