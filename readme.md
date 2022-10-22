## A website from scratch
-HTML

CSS

-Wireframes

-git

-Markdown

## HTML

we started reading a skeletonb (! enter in VS code, than we created the header, linked in CSS and the other two big containers , main and footer)

header contains a logo, a heading and navigation

```html

<header>
        <div>
            <p>My logo</p>
        </div>
        <h1>Personal training</h1>
        <nav>
            <a href="">Training</a>
            <a href="">About us</a>
            <a href="">Contact</a>
        </nav>
    </header>

```
## CSS

Defined primary and secondary colors, add item to the background and text colors

Flex box for the header to allign the 3 elements inside centered and vertically

```css
header {
    background-color: chocolate;
    display: flex;
    flex-direction: column;
    align-items: center;

}
```