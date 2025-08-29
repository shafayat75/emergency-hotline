1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
Answer : The getElementById returns a single element not html collection and The getElementByClassName returns us a html collection of all elements and it is a live collection also that's the different with querySelectorAll method.querySelectorAll Return a static html collection.which one is not update automatically when dom changes. and the another one is querySelector. querySelector return a single element which one is matched with first css selector

2. How do you create and insert a new element into the DOM?
Answer : For creating and insert a new element in into the DOM. I first use document.createElement() for create the element in to the memory. then i use appendChild method to insert it into the document.

3. What is Event Bubbling and how does it work?
Answer : Event bubbling is the process in the DOM is An event starts from clild to it's parent like bubble up. let's give you an example - i have a div and it has a child.when i click in child element then event will be it's parent also. at first it will fire where i cliked then it's parent.if div have any parent and event then div's parent event also fired. like - button > div > body.

4. What is Event Delegation in JavaScript? Why is it useful?
Answer : Event Delegation is a powerful technique in Javascript where instead of using addEventListeners to induvidual child elements.I can add a single addEventListener to the parent Element like ul element.

It's Advantage is it's increase the application Performance and Memory Efficiency and handle the event listener Dynamically.and it's a cleaner way to add addEventListener.

5.What is the difference between preventDefault() and stopPropagation() methods?
Answer : The preventDefault() method stops the browswer's default behavior and the stopPropagaton() Method stop's the event bubbling to up.
