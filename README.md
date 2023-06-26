# Debugging_Leap_Year

<h2> Problem</h2>
When the code is run with it's initial implementation, the program has a<br> 
"TypeError: not all arguments converted during string formatting" error.
<br><br>
This error is produced because when the code was implemented, it was leaving year in str format.
Then in the if statements it was attempting to compare year % 4 which requires year to be an int not a str.
<br>
To fix the error, I cast year to an int as it was being input.
<h2>Instructions</h2>
<ul>
	<li>Read this the code in main.py</li>
	<li>Spot the problems.</li>
	<li>Modify the code to fix the program.</li>
	<li>No shortcuts - don't copy-paste to replace the code entirely with a working solution.</li>
	<li>Fix the code so that it works and when you hit submit it should pass all the tests.</li>
</ul>