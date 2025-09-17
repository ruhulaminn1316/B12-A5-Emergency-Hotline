
**Assignment-005**


**1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?**
answer: getElementById - select one element.
 getElementsByClassName - select all element(same class name).
querySelector - select first matching all using css selector.
querySelectorAll  -select all matching .

**2. How do you create and insert a new element into the DOM?**
Answer: use document.createElement(). then set content then insert with appendChild or prepend.

**3. What is Event Bubbling and how does it work?**
Answer: when An event on a child moves up to its parent->document.

**4. What is Event Delegation in JavaScript? Why is it useful?**
Answer: using a parent's listener to handle child events;useful for dynamic elements and efficiency.

**5. What is the difference between preventDefault() and stopPropagation() methods? **
Answer: preventDefault() stops the browser's default action, while stopPropagation() stops the event from bubbling to parent elements.