for index.html I put:

css/style.css

css/print.css

at the bottom of the index.html file.
I removed the google font as it has very little effect on the appearance of the site.
I changed the print.css to have media='print'

I also inlined the perfmatters.js file and placed it at the bottom of index.html

I made two copies of pizzeria.jpg, one for pizza.html and the other, pizzeria.ico,
for the index.html instance. This icon is 96 by 96 and thus is reduced in size.


for main.js

for all functions:

I changed all relevant querySelectorAll to getElementsByClassName

for updatePositions:

I pulled calculation of sine out of the the inner for loop of the updatePositions function.
I calculated scrollInfo once rather than for each pizza
I calculated Math.sin 5 times rather than once per pizza.

for resizePizzas:

I saved document.getElementsByClassName in a variable so I only have to do the lookup once
I computed dx and newwidth outside the loop from the 0th pizza since all pizzas are the same size
I also placed dx inside the computation for newwidth so I don't have to create another variable

for determineDx
I changed querySelectorAll to getELementById

Steps to run the project
1.
checkout project4 from github.com at
https://github.com/patrickwregan/project4

2. to check index.html, load index.html into your browser
2a. to check code, load index.html into a text editor and read comments
also look for comments above.
3. to check pizza.html, load pizza.html into your browser
3a. to check main.js, load main.js into a text editor and look at comments in code
also look above to all comments aggregated together
