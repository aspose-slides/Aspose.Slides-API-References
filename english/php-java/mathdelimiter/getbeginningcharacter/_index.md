---
title: getBeginningCharacter
type: docs
weight: 50
url: /php-java/mathdelimiter/getbeginningcharacter/
---

# getBeginningCharacter() method

 Delimiter Beginning Character specifies the beginning, or opening, delimiter character. 
 Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces.
 The default: '('.
 
Example:
 
```php
  $delimiter = new MathematicalText("x")->join("y")->enclose();
  $delimiter->setBeginningCharacter('[');
```


