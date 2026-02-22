## Answers to Questions

**1. Difference between `getElementById`, `getElementsByClassName`, and `querySelector / querySelectorAll`**  
- `getElementById(id)` → Single element by ID  
- `getElementsByClassName(className)` → Live HTMLCollection of elements  
- `querySelector(selector)` → First element matching CSS selector  
- `querySelectorAll(selector)` → Static NodeList of matching elements  

**2. How to create and insert a new element**  
```javascript
const newDiv = document.createElement('div');
newDiv.textContent = "Hello World";
newDiv.className = "myClass";
document.body.appendChild(newDiv);
