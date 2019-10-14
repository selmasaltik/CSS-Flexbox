# CSS-Flexbox
This is an informational sharing about CSS Flexbox.

***********************************************************************************************************************************

CSS Flexbox - Mastering the Basics

What is Flexbox?

CSS Flexible Box Module -> one-dimensional layout model

* flexible and efficient layouts
* distribute space among items
* control their aligment

Layout modes

* Block, for sections in a webpage
* Inline, for text
* Table, for two-dimensional table data
* Positioned, for explicit position of an element

Why Flexbox?

* a lot of flexibility
* arrange items
* spacing
* alignment
* order of items
* bootstrap 4 is built on top of the flex layout

Flex Container Properties

* display
  > Create either a block level or inline level flex container.
  * flex
  * inline-flex
* flex-direction
  > Sets the direction of the main axis.
  * row
  * row-reverse
  * column
  * column-reverse
* flex-wrap
  > Control the wrapping of flex items within the container.
  * nowrap
  * wrap
  * wrap-reverse
* flex-flow
  > Short hand for flex direction and flex wrap.
  > flex-flow: <flex-direction> <flex-wrap>
* justify-content
  > Align items and distribute any extra spacing in the parent container.
  > The alignment is always along the main axis.
  * flex-start
  * flex-end
  * center
  * space-between
  * space-around
  * space-evenly
* align-items
  > Align items along the cross axis.
  * flex-start
  * flex-end
  * center
  * baseline
  * stretch
* align-content
  > Aligns lines of content along the cross axis and distribute any extra spacing in the parent container.
  * flex-start
  * flex-end
  * center
  * space-between
  * space-around
  * stretch
  
Flex item properties
  
  * order
    > Control the order of items in the flex container.
    > Integer value
  * flex-grow
    > Dictates what amount of the available space inside the flex container the item should take up.
    > Relative to the other items in the container.
    > Default value is 0-items do not grow.
    > flex-grow value of 1 - flex items grow evenly.
  * flex-shrink
    > Dictates the shrink factor of the flex items when the default size of flex items is larger than the flex container.
    > Relative to the other items in the container.
    > Default value is 1.
  * flex-basis
    > Set the initial size of a flex item.
    > Pixels, percentages or relative units.
    > Default value is auto.
  * flex
    > Short hand for flex grow, flex shrink and flex basis.
    > flex: <flex-grow> <flex-shrink> <flex-basis>
    > Default -> flex: 0 1 auto;
  
flex values
  
  /* One value, unitless number: flex-grow */
  flex: 2;
  
  /* One value, width/height: flex-basis */
  flex: 10em;
  flex: 30px;
  
  /* flex: none | initial | auto */
  /* Two values: flex-grow | flex-shrink */
  flex: 1 30px;
  
  /* Two values: flex-grow | flex-shrink */
  flex: 2 2;
  
  / Three values: flex-grow | flex-shrink | flex-basis */
  flex: 2 2 10%;
  
  * align-self
    > Align the items individually.
    > Values like auto, flex-sart, flex-end, center and stretch.
    > Overrides the align-items value of the flex container.
  

Source: https://www.udemy.com/course/css-flexbox-mastering-the-basics/
        






