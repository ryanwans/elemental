# elemental
Inject reusable, foreign HTML elements into the DOM. 

## Why Use Elemental?
Elemental removes the need for storing reusable HTML elements as strings or
resting in the DOM. Now, you can store all of your reusable elements in a single
file and quickly inject the needed ones into your window.

## Usage
Store the elements:<br>
`elemental.retrieveElements("URL/to/elements.html")`
<br>
To grab the element (in typeof HTMLElement):<br>
`elemental.Elements[NameOfElement]` or `elemental.getElement(NameOfElement)`
