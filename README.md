## FlipText.js

A simple JavaScript component to flip text.

Made with [<3](https://twitter.com/arrowgunz)

### Demo

[http://mohni.sh/fliptext.js/](http://mohni.sh/fliptext.js/)

### Installation

`<script src='fliptext.js'></script>`

### Bookmarklet

<a class="bookmarklet" href="javascript:(function()%7Bfunction%20callback()%7Balert(flipText(prompt('Enter%20text%20to%20flip')%2C%20true))%7Dvar%20s%3Ddocument.createElement(%22script%22)%3Bs.src%3D%22http%3A%2F%2Fmohni.sh%2Ffliptext.js%2Ffliptext.js%22%3Bif(s.addEventListener)%7Bs.addEventListener(%22load%22%2Ccallback%2Cfalse)%7Delse%20if(s.readyState)%7Bs.onreadystatechange%3Dcallback%7Ddocument.body.appendChild(s)%3B%7D)()">FlipText!</a>

### Example

```
flipText("your text")
// => "ʇxǝʇ ɹnoʎ"

flipText("your text", true)
// => "(╯°□°)╯︵ ʇxǝʇ ɹnoʎ"
```

## LICENSE

MIT