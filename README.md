# CSS Selectors

## CSS Selectors Description

### Descendant Selector
```css
A B 
/* selects any B elements that are inside of the element A */
```

### Comma Combinator
```css
A, B
/* selects all A and B elements */
```

### Universal Selector
```css
*
/* selects all elements */
```

### Adjacent Sibling Selector
```css
A + B
/* This selects all B elements that directly follow A. Elements that follow one another are called siblings. They're on the same level, or depth. */
```

### General Sibling Selector
```css
A ~ B
/* A ~ B selects all B that follow a A */
```

### Child Selector
```css
A > B
/* A > B selects all B that are a direct children A */
```

### First Child Pseudo-selector
```css
:first-child
/* p:first-child selects all first child p elements. */
```

### Only Child Pseudo-selector
```css
:only-child
/* span:only-child selects the span elements that are the only child of some other element. */
```

### Last Child Pseudo-selector
```css
:last-child
/* span:last-child selects all last-child span elements. */
```

### Nth Child Pseudo-selector
```css
:nth-child(A)
/* :nth-child(8) selects every element that is the 8th child of another element. */

:nth-child(odd)
/* :nth-child(odd) selects every odd element */

:nth-child(even)
/* :nth-child(even) selects every even element */
```

### Nth Last Child Selector
```css
/* Selects the children from the bottom of the parent. This is like nth-child, but counting from the back! */
:nth-last-child(A)
/* :nth-last-child(2) selects all second-to-last child elements. */
```
