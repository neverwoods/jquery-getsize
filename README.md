# jquery-getsize
Get the size of any element in the DOM even when it's not visible yet

## Installation

```sh
bower install --save jquery-getsize
```

## Usage

```js

jQuery(document).ready(function ($) {

  var sizes = $('.element-selector').getSize();
  
  /*
  {
    width: '100px',
    height: '100px'
  }
  */
   

});
