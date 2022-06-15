---
title: getSubscript
type: docs
weight: 120
url: /php-java/mathnaryoperator/getsubscript/
---

# getSubscript() method

 Specifies a subscript argument that, for example, in the case of an integral, sets the lower limit
 
Example:
 
```php
  $naryOperator = new MathematicalText("x")->nary(MathNaryOperatorTypes.Summation, "x=1", "100");
  $subscriptArg = $naryOperator->getSubscript();
```


