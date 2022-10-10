Chages the color of the background everytime the page is refreshed.
 1. Create the basic HTML page structure
 2. Create the script tags inside the body tag
 3. Inside the script, define a variable that stores all the possible background colors in an array
- next, create a javascript statement that will randomly select one of the collors in the array and 
apply it as the background color each time the page is refreshed.
 - to do that, i have used a document body style property and set it to a randomized value in the bgcolor array index.
 - The value of the index is derived by multiplying a random value (between 0 and 1) this is dome using the Math.random() metod
and multiply it by the length of the array(which is 8 in this case)
 - then i used Math.floor() to round off the value to the nearest whole number. 
so, this gives me the value of the index number in the bgcolor array and each time its oing to be different