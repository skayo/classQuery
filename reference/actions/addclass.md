# addClass

## Description

Adds one or more classes to an element.

## Arguments

If you use external arguments, use the argument's name.  
If you use non-external arguments, use the order of the arguments as written here:

#### classes

A list of classes to add.  
Space-separated if external argument.  
Hyphen-separated if non-external argument.


## Examples

- Add the class 'active' to self at double click: `cq_dblclick_addClass-active_self`  
- Add the classes 'active' and 'awesome' to self at double click: `cq_dblclick_addClass-active-awesome_self`  
- Add the class 'is-active' to self at double click:  
  ```html  
  <li class="cq_dblclick_addClass--_self" data-classes="is-active">Menu Item</li>  
  ```