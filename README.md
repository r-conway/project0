# Project 0
# Rebecca Conway, CS 33A

Web Programming with Python and JavaScript
This website is designed as one homepage (index.html) with three subpages focused on more specific information about my life
(rowing.html, albany.html, and family.html).  Any page can be navigated to from any other by use of the hyperlinks on the top
which are organized using bootstrap columns.  The color scheme of light purple is easily readable and contrasted by the yellow
navigation bar.

The remaining constraints are met in the following ways:
Ordered list: Best Breakfasts in Albany
Unordered list: Attractions in Albany
Table: Of past pets
Photo: Under Albany Attractions, rowing, or the home page
stylesheet: styleproject0.css
5 CSS selectors: .container, .list, #gold, #fact, #name
5 CSS commands: color, background-color,text-align, font-size, border
@media: Found on the style sheet, it changes the background color from lilaic to white for easier reading
Bootstrap component: The radio buttons under rowing
Bootstrap columns: The arrangements of the hyperlinks at the top of the page
SCSS: The SCSS was converted to CSS using the application "Koala" and added under the file name "style.css" (as opposed to the
file styleproject0.css which was written directly in CSS).  The color variable, inheritance, and nestling can be seen in the list
under family.  Color variables are used to denote the shades of blue.  Nestling is used to distinguish the color and size of facts,
even though they share a common class.  And inheritance is shown by how the most specific facts take on the coloring of
the first fact because no color was declared for the specific facts.
