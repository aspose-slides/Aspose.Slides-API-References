---
title: getSuperscript
type: docs
weight: 40
url: /php-java/mathleftsubsuperscriptelement/getsuperscript/
---

# getSuperscript() method

 Superscript
 
Example:
 
```php
  $baseElement = new MathematicalText("X");
  $subscript = new MathematicalText("i");
  $superscript = new MathematicalText("j");
  $leftSubSuperscript = new MathLeftSubSuperscriptElement($baseElement, $subscript, $superscript);
  $sup = $leftSubSuperscript->getSuperscript();
```


