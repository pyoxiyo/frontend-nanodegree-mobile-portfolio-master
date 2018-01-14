
## How to run this application
open `index.html` with your favourite browser!

# fixes i made for `index.html`
1- minified the `css and js `
files

2- unblocked `print.min.css` with a `print` media query

3- inlined `style.min.css` [I learned how to do it from PageSpeed Insights](https://developers.google.com/speed/docs/insights/OptimizeCSSDelivery).

4- compressed and resized the profile pic and the pizzaria image.

5- moved the `link` element that grabs the fonts at the end of the `html` page. 

# fixes i made for `main.js` for `pizza.html`
1- Changed `changePizzaSizes()` to stop the Layout Thrashing.

2- Removed `pizzasDiv` from the `for` loop.

3- Changed `updatePositions()` to stop the Layout Thrashing.

4- In line 545, i made the number of background pizzas change depending on the size of screen, instead of it being 200 pizzas all the time.