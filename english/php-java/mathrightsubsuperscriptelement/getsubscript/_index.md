---
title: getSubscript
type: docs
weight: 40
url: /php-java/mathrightsubsuperscriptelement/getsubscript/
---

# getSubscript() method

 Subscript argument
 
Example:
 
```php
  $baseElement = new MathematicalText("X");
  $subscript = new MathematicalText("i");
  $superscript = new MathematicalText("j");
  $subsuperscript = new MathRightSubSuperscriptElement($baseElement, $subscript, $superscript);
  $sub = $subsuperscript->getSubscript();
```


