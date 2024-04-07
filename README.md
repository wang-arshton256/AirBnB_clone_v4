# AirBnB Clone - RESTful API
This sub-project is a part of the AirBnB Clone project focusing on Web dynamic.

**Requesting your own API** can provide a convenient and efficient way to access data or functionality within your own application.
This can be achieved by creating and hosting your own API using a variety of technologies such as Node.js, Flask, or Django.
Here's an example of creating a basic API endpoint using Node.js and Express:
```
const express = require('express');
const app = express();

app.get('/api/data', (req, res) => {
  const data = {
    message: 'Hello World!'
  };
  res.json(data);
});

app.listen(3000, () => {
  console.log('Server listening on port 3000');
});
```

**An HTML element's style can be modified** using the style property in JavaScript.
Here's an example of changing the font color of an element with the ID myElement to red:
```
const element = document.getElementById('myElement');
element.style.color = 'red';
```

**To get an HTML element's content** using the innerHTML property in JavaScript.
Update an HTML element's content by assigning a new value to the innerHTML property.
Here's an example of getting the content of an element with the ID myElement and updating it to say "Hello World!":
```
const element = document.getElementById('myElement');
const content = element.innerHTML;
element.innerHTML = 'Hello World!';
```

**The DOM (Document Object Model)** represents the HTML document as a tree structure of objects that can be manipulated with JavaScript.
The DOM can be modified by adding, removing, or changing elements, attributes, or text.
Here's an example of adding a new element to the DOM:
```
const parent = document.getElementById('parentElement');
const newElement = document.createElement('div');
newElement.innerHTML = 'New element';
parent.appendChild(newElement);
```

**A GET request can be made to a server **using JQuery's $.ajax() function.
Here's an example of making a GET request to the URL /api/data and logging the response:
```
$.ajax({
  url: '/api/data',
  method: 'GET',
  success: function(response) {
    console.log(response);
  },
  error: function(error) {
    console.error(error);
  }
});
```

**Also, a POST request can be made to a server** using JQuery's $.ajax() function and specifying the method as 'POST'.
Here's an example of making a POST request to the URL /api/data with a JSON payload and logging the response:
```
$.ajax({
  url: '/api/data',
  method: 'POST',
  data: JSON.stringify({name: 'John', age: 30}),
  contentType: 'application/json',
  success: function(response) {
    console.log(response);
  },
  error: function(error) {
    console.error(error);
  }
});
```

**To listen to DOM events** using the addEventListener() method in JavaScript.
Here's an example of listening to the click event on an element with the ID myButton and logging a message when clicked:
```
const button = document.getElementById('myButton');
button.addEventListener('click', function(event) {
  console.log('Button clicked');
});
```

**To listen/bind to user events in a web application**, JavaScript event listeners can be used. Here are some examples of how to listen/bind to different types of user events:

Click Event:
To listen to a click event on an element, the addEventListener method can be used,  passing the event type click as the first argument, and the function that will be called when the event is triggered as the second argument.
Example:
```
const button = document.querySelector('#myButton');

button.addEventListener('click', function(event) {
  // handle the click event here
});
```
Keydown Event:
To listen to a keydown event on the document or on a specific element, the addEventListener method can be used and passing the event type keydown as the first argument, and the function that will be called when the event is triggered as the second argument.
Example:
```
document.addEventListener('keydown', function(event) {
  // handle the keydown event here
});

const input = document.querySelector('#myInput');
input.addEventListener('keydown', function(event) {
  // handle the keydown event on the input element here
});
```
Submit Event:
To listen to a submit event on a form element, the addEventListener method can be used, passing the event type submit as the first argument, and the function that will be called when the event is triggered as the second argument.
Example:
```
const form = document.querySelector('#myForm');

form.addEventListener('submit', function(event) {
  // handle the submit event here
});
```
Change Event:
To listen to a change event on an input element, the addEventListener method can be used, passing the event type change as the first argument, and the function that will be called when the event is triggered as the second argument.
Example:
```
const input = document.querySelector('#myInput');

input.addEventListener('change', function(event) {
  // handle the change event on the input element here
});
```
Note: The above examples assume that the element to listen to the event on have already been selected using methods like document.querySelector.


## Bugs
No known bugs at this time. 

## Authors
Wangutusi Arshton - [Github](https://github.com/wang-arshton256) / [Twitter](https://twitter.com/wangarshtonc)
 
Victor Chesachi Kalu - [Github](https://github.com/chesahkalu) / [Twitter](https://twitter.com/ai_optimizer)

## License
Public Domain. No copy write protection. 
