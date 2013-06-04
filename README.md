# jquery-find-by-name

<a href="http://apostrophenow.org/"><img src="https://raw.github.com/punkave/jquery-getOuterHTML/master/logos/logo-box-madefor.png" align="right" /></a>

`jquery-find-by-name` provides a less bug-prone way to find elements by their name attribute. In particular, when the name attribute is stored in a variable it is very bug-prone to write a selector for it by hand every time.

## How to Use

    $('.my-element').findByName('age');

And especially:

    $.each(fields, function(i, field) {
      $('.my-element').findByName(name);
    });

### Requirements

You need jQuery, of course. `jquery-find-by-name` is actively supported with jQuery 1.9 and 2.0 but should work fine with older versions.

## About P'unk Avenue and Apostrophe

`jquery-find-by-name` was created at [P'unk Avenue](http://punkave.com) for use in Apostrophe, an open-source content management system built on node.js. If you like `jquery-find-by-name` you should definitely [check out apostrophenow.org](http://apostrophenow.org). Also be sure to visit us on [github](http://github.com/punkave).

## Support

Feel free to open issues on [github](http://github.com/punkave/jquery-find-by-name).

<a href="http://punkave.com/"><img src="https://raw.github.com/punkave/jquery-find-by-name/master/logos/logo-box-builtby.png" /></a>

