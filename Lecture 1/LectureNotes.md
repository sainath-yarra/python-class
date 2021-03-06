# Lecture 1
![Python Logo](https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg)
## Introduction to Python

### History
Guido Van Rossum is a dutch programmer best known as the author of the Python programming language, for which he was the "_Benevolent dictator for life"(BDFL)_ until he stepped down from the position in July 2018.

"_Benevolent dictator for life"(BDFL)_ is a title given to a small number of open-source software development leaders, typically project founders who retain the final say in disputes or arguments within the community.

In December 1989, Van Rossum had been looking for a "'hobby' programming project that would keep him occupied during the week around Christmas" as his office was closed when he decided to write an interpreter for a "new scripting language". Being a big fan of "_Monty Python's Flying Circus_", he named the language after this British surreal sketch comedy series.

### Compiler Vs Interpreter
Interpreter is a program that executes other programs. It is a layer between your code and computer hardware. In a nutshell, compiler lists out all the errors at once where as interpreter doesn't proceed when it encounters an error.

### Versions of Python
If you are new to Python then choosing to learn Python 3 is better unless you are working for a company that has libraries that work only with Python 2.
Support for Python 2 ends in 2020. Even though Python 2 and Python 3 are incompatible with eachother Python's fundamentals are the same in both versions. Both the versions differ in ways many users find minor. Therefore it is possible to write a version-neutral  code that runs on both platforms.
#### Python 2
When I say Python 2 I mean Python 2.7 it is a version that was developed to transition into Python 3.
Python 2 is used for automation, most core applications and web development until recent days. The reason for the delay is compatability of libraries. Python 2.7 has been around for about a decade.
#### Python 3
Data science, machine learning, artificial intelligence and all that fun stuff has great support on Python 3

### Python Style Guide
A programming style guide is a cluster of rules or guidelines that specify how the program should be written. This makes it much easier for a user to read the program. Python follows PEP 8 which was created on 5 Jul 2001. PEP stands for Python Enhancement Proposal.

### Features of Python
#### Object-Oriented
An object is something that has some properties such as a **bike**. It has:
* Two wheels,
* A handle,
* Brakes,
* Horn, etc
Here, wheels, handle, brakes, horn are all properties of bike.
Python treats everything in it as an object.
This concept will be explained in later session of the course.
#### Open source
Python is free. You don't have to buy it to use it or pay someone before you sell it. You can edit anything you wish to change from the roots, but of cource its not easy to do that. Unlike some corporate software where you have to live with decisions made by others, its good to know that you can always take control if you need to.
#### Portable
Portability in Python is as easy as copying and pasting the code in the required oparating system.
#### It's Powerful
This is also one of the things that's better explaind as the course proceeds.
#### Mixable
Python can be attached to components written in other languages with ease.
#### It's relatively easy to use and learn
When compared to alternatives like C, C++, Java and C#, Python is easy to implement and also very easy to learn.

### Installing Python
#### On Android
Pydroid 3 which is avilable in [play store](https://play.google.com/store/apps/details?id=ru.iiec.pydroid3).
#### On PC
Python is avilable for download on the official [website](https://www.python.org/). Once downloaded check Add Python to PATH box and then click Install Now and proceed with the install.

After install you can verify your install by typing `python --version` which will return the version of python you have installed.

### Choosing an IDE
When it comes to choosing an IDE, you have a variety of options* to choose from. Few of the most popular ones are:
1. [Pycharm](https://www.jetbrains.com/pycharm/download/) by JetBrains
1. [Visual Studio Code](code.visualstudio.com/download) by Microsoft
1. [Atom](https://atom.io/) is Open source and can be found on [GitHub](https://github.com/atom)
1. [Komodo](https://www.activestate.com/products/komodo-ide/downloads/edit/) by ActiveState
1. [Sublime text](https://www.sublimetext.com/3) by Sublime HQ
1. [Eclipse](https://www.eclipse.org/downloads/) by Eclipse Foundation

*you may have to install extentions for some of the IDEs mentioned.

### Hello World Program
First thing you learn in any programming language or any language for that matter is saying hello. This is how you say hello in python:

`print("Hello world!")`

typing this line in the python interpreter should return Hello world! in text. If you see this without any errors you are good to go.

### Web Frameworks based on Python
The two most popular web frameworks in python are:
* [Flask](https://flask.palletsprojects.com/en/1.1.x/)
* [Django](https://www.djangoproject.com/)
#### Flask
Flask has a light weight and modular design. It is highly flexible, the configuration is even more flexible than that of Django, giving you plenty of solutions for every production need. 
#### Django
> Django makes it easier to build better Web apps more quickly and with less code.

Django is highly scalable. Scalability means that at whatever scope or level, the technology can be implemented. It is super secure, thoroughly tested and provides rapid development.

### Why Python good?
After all one should know all the perks of what they are learing. So the perks of Python and why most people choose to learn Python are as follows:
#### Software quality
* Readability
    * With readability you get:
        1. Reusability
        1. Maintainability
* Coherence (The quality of being logical and consistent)
* Object oriented
#### Developer Productivity
* Python takes one-third to one-fifth size of equvalent C++ or Java code.
* Less to type (very less redundant code, can do more with less code)
    * Less to debug
    * less to maintain
* Program runs as soon as you execute it.
    * No lengthy compilation time
    * No need to do all the linking steps required for other traditional laguages like C, C++ or Java
#### Program Portability
* Python is portable, it supports all the major platforms like Windows, Mac, Linux and more.
#### Support Libraries
* There is a good standard library built in that handles all the portability for you.
* Third pary support for Python libraries is awesome too.
    * NumPy is a third party extention that is free and more powerful than a Matlab Numeric programming system. 
#### Component Integration
Parts of code written in Python can easily communicate with other parts of an application (that maybe written in another language say C++ for instance).

### Why Python bad?
Even though Python has a lot of advantages, it has one major drawback - _EXECUTION SPEED_.
Compared to fully compiled programming laguages like C and C++, Python is slower in execution speed. This disadvantage can be overcome by integrating Python with languages like C or C++ (which work faster) at crucial parts of code that requre faster execution time.