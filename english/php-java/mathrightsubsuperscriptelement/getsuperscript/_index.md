---
title: getSuperscript
type: docs
weight: 50
url: /php-java/mathrightsubsuperscriptelement/getsuperscript/
---

# getSuperscript() method

 Superscript argument
 
Example:
 
```php
  $baseElement = new MathematicalText("X");
  $subscript = new MathematicalText("i");
  $superscript = new MathematicalText("j");
  $subsuperscript = new MathRightSubSuperscriptElement($baseElement, $subscript, $superscript);
  $sup = $subsuperscript->getSuperscript();
```

