1.What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

Ans: The difference between **getElementById, getElementByClassName, and querySelector / querySelectorAll** is 
<table border=1 width="100%" >
  <tr>
    <td>No.</td>
    <td>getElementById</td>
    <td>getElementsByClassName</td>
    <td>querySelector / querySelectorAll</td>
  </tr>
  <td>1.</td>
  <td>This property is used to get/catch/manipulate any html elements by there id.</td>
  <td>This property is used for get/catch/manipulate any html elements by their class name.</td>
  <td>These properties are used for get/catch/manipulate any html elements as like css.</td>
</table>

2.How do you create and insert a new element into the DOM?

Ans:
How I create and insert a new element into the DOM:
<br>
Firstly, I have to use this (createElement) DOM property to create any element. and then I have to input the tag name of the element I want to create.
(e.g.  `const child = document.createElement('div')`.
<br>
Secondly, I have to call/get the parentNode where I want to append the newly created element.
<br>
(e.g. `document.getElementByid('parent-container')`.
<br>
Lastly, I have to append the new element to the parentNode.
<br>
(e.g.  `document.getelementByid('parent-container').appendChild(child)`.

3.What is Event Bubbling and how does it work?

