# gridPage2
<h1> hosting link: </h1>

https://trishadas13.github.io/gridPage2/

<hr>
![image](https://github.com/trishaDas13/gridPage2/assets/126088849/2fbbbb7e-2416-4000-ae5a-ad299338b75c)
![image](https://github.com/trishaDas13/gridPage2/assets/126088849/52a6ef0e-4c29-489d-be5b-a184178ee566)
Container (<div> with Class "container"):

The main container that holds the entire content of the section.
Grid (<div> with Class "grid"):

Within the container, a grid layout is established to organize the content.
Item 1 (<div> with Class "item1"):

This division represents the first item within the grid layout.
Navigation Bar (<div> with Class "navbar"):

Inside "item1," a navigation bar is created using a div element with the class "navbar."
The navigation bar contains a set of buttons and an image logo.
Home Button (<button>):

A button labeled "Home" is included in the navigation bar.
About Button (<button>):

Another button labeled "About" is added.
Logo (<img>):

An img element is used to display the logo image. The image's source URL is set to a Twitter logo, and the "alt" attribute provides alternative text for accessibility. The "width" and "height" attributes control the image's dimensions.
Menu Button (<button>):

A button labeled "Menu" is placed in the navigation bar.
Contact Button (<button>):

Finally, a "Contact" button is included in the navigation bar.

![image](https://github.com/trishaDas13/gridPage2/assets/126088849/649b9f4c-eefa-4564-8df6-d9f8aaaaf857)

*: This is a global CSS selector that resets margin, padding, and box-sizing properties for all elements to ensure consistent styling across different browsers.

.container: Represents a container that spans the entire viewport height (100vh).

.grid: This class defines a grid layout with 16 columns and 6 rows, each row having a height of 6rem. The total grid height is set to 36rem.

.item1, .item2, .item3, .item4, .item5, .item6, .item7, .item8, .item9, .item10: These classes are assigned to different grid items within the .grid container. They have a black border and a small amount of padding.

.item1: This item spans all 16 columns and the first row. It's used as a header section and contains a navigation bar styled with a dark background color and white text.

.navbar: Represents the navigation bar within the .item1 container. It has a width of 70% and uses flexbox to horizontally align and space out its contents.

button: Represents buttons within the navigation bar. They have a dark background color, white text, and rounded corners.

Please note that the provided code doesn't include specific content or styling for the other items (.item2 to .item10). You can continue adding content and styles to these items as needed for your design.

![image](https://github.com/trishaDas13/gridPage2/assets/126088849/d7a9d7fb-e839-4359-8785-e17eddd130b7)
![image](https://github.com/trishaDas13/gridPage2/assets/126088849/e4dd5d4f-5f50-4387-ae21-c394e3ea213b)

Container (<div> with Class "container"):

The main container that holds the grid layout and additional content.
Grid (<div> with Class "grid"):

Within the container, a grid layout is established to organize the images.
Item 2 to Item 10 (<div> with Class "item2" to "item10"):

These divisions represent individual items within the grid layout.
Each item contains an img element displaying an image. The "src" attribute specifies the image file's path, and the "alt" attribute provides alternative text for accessibility. The "height" and "width" attributes control the image dimensions, set to 100% to fill the available space.
Content Outside Grid:

Outside the grid, there is a link (URL: https://www.podia.com/pricing) as text content.
Closing Tags:

The code ends with the necessary closing tags for the div, body, and html elements.

![image](https://github.com/trishaDas13/gridPage2/assets/126088849/6897cd8d-cfb2-4163-ba4d-304b5500ac61)
![image](https://github.com/trishaDas13/gridPage2/assets/126088849/6077cac8-d508-4627-aba0-1973b9d3c7e0)


I've created a container called .container that takes up the full width of the viewport and has a height of 100vh (viewport height). Inside this container, I've defined a grid layout with the class .grid. This grid has 16 columns, each taking up 6.25% of the container's width, and 6 rows, each with a fixed height of 6rem. This grid system provides a structured layout for placing elements.

I've positioned various items within this grid using the grid-column and grid-row properties. For instance, I've placed .item2 in the 2nd row, spanning columns 1 to 4. .item3 is positioned in the 2nd row, spanning columns 4 to 9. Similarly, .item4 covers columns 9 to 12 in rows 2 to 5, and .item5 spans columns 12 to 17 in the same rows. This pattern continues for other items like .item6, .item7, and so on, with specific positions within the grid.

I've also defined a navigation bar (.navbar) that occupies the full width of the .item1. To create a balanced layout, I've used flexbox properties like display: flex, justify-content: space-between, and align-items: center. This aligns the contents of the navbar evenly and ensures proper spacing. Additionally, I've styled the buttons in the navbar with a dark background color (rgb(14, 13, 13)) and white text. The buttons have rounded corners using border-radius: 8px to enhance their appearance.

Overall, by establishing this grid structure and positioning items within it, I've laid a solid foundation for designing and styling my webpage. This grid-based approach provides organization and responsiveness, allowing me to easily add content and further customize the design as needed.
