# Shoe Page Ass-4 CSS

## Project Description
The "Shoe Page" project is a simple web page that showcases a single shoe product. It is designed using HTML and CSS to create an attractive and informative product display.

## HTML Structure

### Container and Wrapper (`<div class="container">`, `<div class="wrapper">`)
- The container and wrapper elements create the main structure of the page.
- The description and image of the shoe are placed within the wrapper.
- The container has a background gradient with a skew effect for a visually appealing design.

### Shoe Description (`<div class="description">`)
- The description section contains information about the shoe product.
- It has multiple paragraphs with product details and Lorem Ipsum text.
- The text is styled with white color for readability.

### Shoe Image (`<img class="shoe">`)
- The shoe image is displayed with a fixed width and height.
- It has a hover effect that enlarges the image for a closer look.

## CSS Styles and Properties

### Global Styles (`*`)
- Resets margin, padding, and box-sizing for all elements to create a consistent layout.

### Container (`<div class="container">`)
- `.container`:
  - `width: 100%;`: Makes the container span the entire width.
  - `height: 100vh;`: Sets the container height to the viewport height.
  - `position: relative;`: Establishes a relative positioning context.
  - `overflow: hidden;`: Hides overflowing content.

- `.container::after`:
  - Creates a skewed background gradient using linear gradients.
  - Adds a shadow effect to the container.

### Wrapper (`<div class="wrapper">`)
- `.wrapper`:
  - `width: 85%;`: Sets the width of the wrapper to 85% of its parent.
  - `height: 75%;`: Sets the height of the wrapper.
  - `margin: auto;`: Centers the wrapper horizontally.
  - `padding: 2%;`: Adds padding to the wrapper.
  - `margin-top: 7.5%;`: Adds margin at the top of the wrapper.
  - `background: linear-gradient();`: Applies a gradient background.
  - `box-shadow: 0px 0px 10px #000000;`: Adds a shadow to the wrapper.

### Shoe Description (`<div class="description">`)
- `.description`:
  - `max-width: 40%;`: Sets the maximum width of the description section.
  - `color: #ffffff;`: Sets the text color to white.

- `.description h1`:
  - `font-size: xx-large;`: Sets the font size for the heading.
  - `margin-bottom: 30px;`: Adds margin at the bottom of the heading.

- `.description p`:
  - `font-size: large;`: Sets the font size for paragraphs.
  - `margin-bottom: 50px;`: Adds margin at the bottom of paragraphs.
  - `line-height: 20px;`: Sets the line height for paragraphs.

### Shoe Image (`<img class="shoe">`)
- `.shoe`:
  - `width: 600px;`: Sets the fixed width of the shoe image.
  - `height: 300px;`: Sets the fixed height of the shoe image.
  - `position: absolute;`: Positions the image absolutely.
  - `right: 0px;`: Aligns the image to the right.
  - `top: 10%;`: Sets the top position.

- `.shoe:hover`:
 - `width: 900px;` increases the image width to 900 pixels on hover, creating a zoomed-in effect.
 - `height: 600px;` increases the image height to 600 pixels on hover, maintaining the aspect ratio for enlargement.
 - `right: 0px;` keeps the image aligned to the right edge of its container.
 - `top: 15px;` adjusts the image's vertical position 15 pixels down from its original position during hover.

