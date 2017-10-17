# Progtester
Progtester tests your program against the tests provided by the teacher and returns the results. If test fails it returns the diff of your files.

**It is opinionated by default.**
Every progtests exercise must be in its own folder and your script must be named ``main.c``.
In that folder there must be a ``tests`` folder.

-- progtest_exercise_1<br/>
&nbsp;&nbsp;&nbsp;&nbsp;-- tests<br/>
&nbsp;&nbsp;&nbsp;&nbsp;main.c
   
It's in very early stage so any new Pull requests are welcomed!


## Usage
``progtester ./progtest_exercise_1``
If you have colordiff installed progtester will use it instead of normal diff. It's better to clearly see what line is different.

## Installation
Copy the progtest to your ``/usr/local/bin`` directory or place it wherever you want.
