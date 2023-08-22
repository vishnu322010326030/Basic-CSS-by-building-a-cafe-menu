# Basic-CSS-by-building-a-Cafe-Menu

HTML (Hypertext Markup Language)
HTML is the standard markup language used to structure content on the web. It provides a way to define the structure and elements of a web page, making it possible to display text, images, links, forms, and more in a structured manner. HTML uses a set of predefined tags, each serving a specific purpose, to create the desired layout and functionality of a web page.

Key HTML concepts:

Tags: HTML uses tags to define elements. Tags are enclosed in angle brackets, such as <tagname>. They usually come in pairs—an opening tag and a closing tag.
Attributes: Tags can have attributes that provide additional information about an element. Attributes are defined within the opening tag and provide properties like src, href, class, etc.
Elements: Elements are made up of tags and their content. For instance, a paragraph element can be defined using the <p> tags.

<!DOCTYPE html>
<html>
<head>
    <title>My Web Page</title>
</head>
<body>
    <h1>Welcome to My Page</h1>
    <p>This is a sample paragraph.</p>
    <a href="https://www.example.com">Visit Example.com</a>
</body>
</html>

CSS (Cascading Style Sheets)
CSS is used to style and visually enhance the elements created with HTML. It provides a way to control the layout, colors, fonts, spacing, and other visual aspects of a web page. CSS allows for separation of content and presentation, making it easier to maintain and update the appearance of a website.

Key CSS concepts:

Selectors: Selectors target specific HTML elements to apply styles to. They can target elements by tag name, class, ID, or other attributes.
Properties: Properties define the visual styles of elements, such as color, font-size, margin, etc.
Values: Values are assigned to properties and determine how the styles are applied. For instance, color: blue; sets the text color to blue.
Selectors and Declarations: Selectors are combined with declarations (properties and values) inside curly braces to create CSS rules.

/* Styling the body element */
body {
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
}

/* Styling headings */
h1 {
    color: #333;
}

/* Styling paragraphs */
p {
    font-size: 16px;
    line-height: 1.5;
}


Connecting HTML and CSS
To apply CSS to HTML elements, you link your CSS file within the HTML document using the <link> tag. Place this tag inside the <head> section of your HTML document.

<!DOCTYPE html>
<html>
<head>
    <title>My Styled Page</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <h1>Welcome to My Styled Page</h1>
    <p>This paragraph has a custom style.</p>
</body>
</html>

