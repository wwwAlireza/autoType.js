# autoType.js
Auto-typing with JavaScript <br>
# how?
It takes the ```text```, the ```element``` and the ```duration``` from you and prints the letters of the text in that <br>
element word for word according to the duration (as if it were being typed);
# how to use?
First link the autoType.js file to the page before all scripts <br>
```html
<script src="autoType.js"></script>
```
Then use the writer function to use autoType <br>
<h2>Example :</h2>
```javascript
const p = document.querySelector("#myParagraph")
writer("Hello World", p, 230)
```
