# Chapter 4: Objects basics

This repo is to document the basics about objects in JavaScript. All information used as a reference the book [JavaScrip Info](http://javascript.info)

## Objects

In JavaScript there are **8 data types** seven of them are called _"primitive"_, because their values contain only a single thing (be it a string or a number).

In constrast, objects are used to store keyed collections of various data and more complex entities.

An object can be created with figure brackets `{}` with an optional list of properties. **A property is a "key:value" pair**, where `key` is a string (also called a "property name"), and `value` can be anything.

We can imagine an object as a cabinet with files. Every piece of data is stored in its file by the key, it's easy to find a file by its name or add/remove a file.

![object analogue of a cabinet with files](./assets/img/figure1.png)

An empty object ("empty cabinet") can be created using of two syntaxes:

```
let user = new Object(); // "object constructor" syntax
let user = {}; // "object literal" syntax
```

![empty object representation](./assets/img/figure2.png)

It's more common to use figure brackets to declare an empty object. That declaration is called an _object literal_.

