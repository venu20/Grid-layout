Grid Layout
- Grid means #### A pattern of horizontal and vertical lines that cross each other to make a set of squares.#### The set of squares which form rows and columns.
- Whenever you wanted to create a webpage using GRID. Think of your UX design as a grid , that means divide your headers, footers, content, sidenav or nav like they are going to stay in multiple of rows or multiple columns. Just draw horizontal and vertical lines on the UX comp with specified number of row and columns like below

### Set columns
- grid-template-columns
  ```
  grid-template-columns: 200px 300px
  grid-template-columns: repeat(3, 200px)
  grid-template-columns: auto auto; // 'auto' set the width based on the content. It will try to set the content in the given viewport width. It doesn't create horizontal scroll if the content width is more than viewport width.
  grid-template-columns: 40% 60%;
  grid-template-columns: max-content max-content; // It will set the column widths as maximum. It will create a horizontal/vertical scroll to set the content in the viewport 
  grid-template-columns: 1fr 1fr;
  grid-template-columns: 40% 60%;

  ```
- grid-auto-columns
