# Google Fonts and CSS Hover Demo

## Using Google Fonts

See the `<head>` in `index.html` which links [Google Fonts](https://fonts.google.com) Lato and Saira - Google Fonts provides you with the `<link>` element for adding fonts, and the CSS `font-family` property:

In `index.html`:
```html
<link href="https://fonts.googleapis.com/css?family=Roboto:
    100,100i,300,300i,400,400i,500,500i,700,700i,900,900i|
    Saira+Stencil+One&display=swap&subset=cyrillic,cyrillic-ext,
    greek,greek-ext,latin-ext,vietnamese" rel="stylesheet">
```

In `styles.css`:

```css
h1,
h2,
h3,
h4,
h5,
h6 {
    font-family: 'Saira Stencil One', cursive;
}
```

## Using the CSS Hover Pseudo-class

Check [W3School's](https://www.w3schools.com/css/css_pseudo_classes.asp) resource on CSS Pseudoclasses, especially if you would like to change the appearance of `<a href="">` elements when they are `visited`, unvisited, `active` or `hover`ed over.

The `:hover` Pseudo-class can be used to add CSS properties to many elements when the mouse is hovered over the element:

See `styles.css` for more examples, the following selects all `<h1>` elements and makes them red and the cursor a pointer when the mouse is hovered over the `<h1>`:

```css
h1:hover {
    color: red;
    cursor: pointer;
}

```