# paper-checklist
Polymer based multi select component which supports a checklist based selection. Uses material design.

Supports both declative and javascript way of providing list elements.

```html
<paper-checklist>
  <ul>
    <li>Bull Dog</li>
    <li>American Bull Dog</li>
    <li>French Bull Dog</li>
    <li>Pug</li>
    <li>Chihuahua</li>
</paper-checklist>
```

```javascript
document.querySelector('paper-checklist').checklistData = ['ABC', 'BCD', 'CDE'];
```
