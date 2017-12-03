# Tock-Too
A (very) short program to test the TOCTTOU problem.<br>
TOCTTOU stands for 'Time of check to time of use', you can learn more about this problem on <a href="https://en.wikipedia.org/wiki/Time_of_check_to_time_of_use">this Wikipedia article!</a>

<h3>Instructions to run the program</h3>
-To run this program in your computer you need to <a href="https://www.python.org/downloads/">download and install Python 3.</a><br>
-To execute from the command line on a Ms Windows system you need to <a href="https://docs.python.org/2/using/windows.html">add Python to the PATH environmental variable.</a><br>

<h5>From the command line:</h5>
1. Open a terminal <br>
2. Navigate to the folder where the file is found <br>
3. On the command line execute: <br>
> python3 TOCTTOU.py  <br>
4. Do not hesitate to contact me if you have any problems running this program <br>

<h5>From a Python Interpreter:</h5>
1. Open Python <br>
2. On the prompt execute: <br>
> exec(open("**path**/TOCTTOU.py").read())< <br>
 <br>
Replace **path** with the local path to the folder that contains the file TOCTTOU.py <br>
3. Do not hesitate to contact me if you have any problems running this program <br>


<h3>Test Instructions:</h3>
Run file <b>TOCTTOU.py</b> as instructed above.

<b>Test I - </b>Run the program normally, edit the file and save the changes.<br>
<b>Test II - </b>Run the program, then remove your writing rights before trying to save the changes.<br>
<b>Test III - </b>Run the program, without any writing rights on the file.<br>
<b>Test IV - </b>Turn your writing permissions back on. Run the program normally, edit the file then remove it before trying to save any changes.<br>

