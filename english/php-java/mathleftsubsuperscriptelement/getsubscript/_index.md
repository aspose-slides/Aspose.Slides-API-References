---
title: getSubscript
type: docs
weight: 30
url: /php-java/mathleftsubsuperscriptelement/getsubscript/
---

# getSubscript() method

 Subscript 
 
Example:
 
```php
  $baseElement = new MathematicalText("X");
  $subscript = new MathematicalText("i");
  $superscript = new MathematicalText("j");
  $leftSubSuperscript = new MathLeftSubSuperscriptElement($baseElement, $subscript, $superscript);
  $sub = $leftSubSuperscript->getSubscript();
```


