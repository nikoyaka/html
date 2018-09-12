# html

Grid represents 12-column system for different size of screen. 
Key points: 
large: screen size more or equal to 1200px	col-lg-*
middle: screen size between 992px and 1200px	col-md-*
small: screen size between 768px and 992px	col-sm-*

all this classes specify what part of screen width is assigned for an element with this class value. 
For example:
col-md-3 means that the element occupies quarter of current screen width provided that the width  ranged from 992px to 1200px.

Class "container": sets concrete width bounds for successors.


Classes: clearfix, pull-left, pull-righ
clearfix: clears float layouts for children.
pull-left and pull-right: assign left- and right-alignment accordingly.


Classes: flex, flex-row, flex-column, space-between, y-center, x-start, x-end - manage the alignment and navigation of components inside container.

flex-row: set a horizontal direction.
flex-column: set a vertical direction.
space-between: elements aligned on the main x-axis with as follows - first element is situated at the beggining of flex-container, the last element is situated at the end. Free space is devided evenly by other elements.
y-center: aligns elements inside flex-container at the center by y-axis.
x-start: aligns elements inside flex-container at the begining by x-axis.
x-end: aligns elements inside flex-container at the end by x-axis.



