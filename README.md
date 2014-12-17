Ripple Button
=========

A ripple button inspired by Google material design and modified from MAWButton Plugin of Michael Chen , Will Huang , Amin Lee

[Demo site](http://nhipsinhhoc.vn)

Required
========

 - jQuery (https://code.jquery.com/jquery-1.11.1.min.js)
 - jQuery Color (https://code.jquery.com/color/jquery.color-2.1.2.min.js)
 
Browser Support
===============

Modern browser like Chrome, Safari, FireFox...etc.

Usage
=====
First of all, you have to inlcude the style.

```html
<link rel="stylesheet" href="jquery.ripple.css">
```

And include script as well.  

```html
<script src="jquery.ripple.js"></script>
```  

You may add some elements like this:  
```html
<a class="button">Link Button</a>
<button>Pure Button</button>
```

To init the ripple button with default options:

```html
<script>
    $('a.button, button').ripple();
</script>
```
or with custom options:   
```html
<script>
    $('a.button, button').ripple({
        speed : 222,
        alpha : 0.222
    });
</script>
```

Options
=======
|Option|Default|Type|Description|
|:-----|:------|:---|:----------|
|`speed` | 333   |int | The duration which are given in milliseconds of effect.|
|`alpha` | 0.333     |int | The transparency alpha of the ripple.|
|`transitionEnd`| function(){} | function | Callback after transition end. | 


LICENSE
=======
The MIT License (MIT)

Copyright (c) 2014 Tung Pham

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.