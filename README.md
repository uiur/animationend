# animationend
Wait for CSS transition/animation end

``` javascript
var animationEnd = require('animationend')

animate(element)

animationEnd(element).then(function(event) {
  // called on transitionend or animationend
})

animationEnd(element, function(event) {
  // also you can use a normal callback
})
```

## License
MIT
