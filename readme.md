
##1 getElementById will find one element same class name elemants.
querySlector finds the first element matching a CSS selector.
querySelectorall finds all elements matching a CSS selectorwith specific id.
getElementByClassName will finds all the same class name elemants.
querySlector finds the first element matching a CSS selector.
querySelectorall finds all elements matching a CSS selector



##2 creating and appending elements first off all you have to create a div or other elements useing document . create element and most important that have to store a variable then name. useing text content = "type anthing " that have to append into parentElement. for example if you went to appent into body than what you have to do is document.body.appendChild(variableName)




##3 event bubbling event bubbling means when an event occurs on an element it bubles up. for example you have a div here is another div inside first div. you add addEventListner both div then if you click child div it will show you clicked both div cause bubbling up.



##4Event delegation event delegation means attaching a single event listner to parent element instead of adding listeners to multiple child elements.




##5 Event methods event.preventDefault() is using for changing forms default behaveior. if you click on submit button then page will auto realoding, for stop this action we use event.preventDefault().event.stop propagation() stop the event from bubbling up to parent elements.