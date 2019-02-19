# CSS: The Box Model

## Which languages does the browser understand?

* JavaScript
* HTML (XHTML)
* CSS

## This Week

* HTML 
  - HyperText Markup Language
    - Document that can be linked to another document
  - Structure of what's being viewed
  - Markup language
* CSS
  - Cascading Style Sheets
  - It's what makes your HTML look pretty
* JavaScript  
  - Behavoir of our application.
  - User interacation

## HTML

### Semantic HTML

* html tags should be used to describe the content
* html has nothing to do with how the content looks

http://html5doctor.com/downloads/h5d-sectioning-flowchart.png

## CSS

https://i.imgur.com/Q3cUg29.gif

## The Box Model

* The browser renders everything as a box (a rectangle)

### Dev Tools!!!!

```css
* {
  outline: solid 1px red !important;
}
```

## Box Sizing

* `background-clip`
* `box-sizing`

## CSS Resets

https://github.com/necolas/normalize.css/

## Block-level vs. Inline

* block will take up the entire width of the page 
* block can have a width and height set
* inline won't do either.

https://css-tricks.com/almanac/properties/d/display/

## Layouts with float

https://css-tricks.com/all-about-floats/

* `float`
* `clear`
* `overflow`

---

# CSS is hard

* you can have as many classes as you want on an element, but only 1 id.
* ids are unique to each element. 

## Selectors

* combinators
* Pseudo-classes

## Specificity

1. !important
2. inline styles
3. id
4. class
5. tag name
6. order

* clear distinct "labels" for clear distinct styles
* make things less specific, only use classes, unless you need to use something else.

## Position

https://css-tricks.com/almanac/properties/p/position/

## Links

* Karl's lecture notes: https://github.com/jensen/css-notes/
* Karl's breakout notes: https://github.com/jensen/csshard-notes
* [CSS Flow Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flow_Layout)
* [CSS Combinators](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors#Combinators)