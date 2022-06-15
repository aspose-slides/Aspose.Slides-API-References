---
title: setEndingCharacter
type: docs
weight: 140
url: /php-java/mathdelimiter/setendingcharacter/
---

# setEndingCharacter(char) method

 Delimiter Ending Character specifies the ending, or closing, delimiter character. 
 Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces.
 The default: ')'.
 
Example:
 
```php
  $delimiter = new MathematicalText("x")->join("y")->enclose();
  $delimiter->setEndingCharacter(']');
```


