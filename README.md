# php-html-in-string-using-html-function

Adds support for highlighting HTML within PHP strings using the `html()` custom function in VSCode.
This extension is an adaptation of the extension [php-html-in-string](https://github.com/zoeyfrisart/php-html-in-string)


## Features

Enable HTML highlighting within PHP strings by echoing HTML code using the `html()` custom function.

```php
function html($content) {
  echo $content . "\n";
}

html('<div class="my-div">This content will be <strong>highlighted</strong> as HTML code, not as a long string</div>');
```
