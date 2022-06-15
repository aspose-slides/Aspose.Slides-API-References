---
title: getAlignScripts
type: docs
weight: 20
url: /php-java/mathrightsubsuperscriptelement/getalignscripts/
---

# getAlignScripts() method

 Specifies the alignment of subscript/superscript. 
 When true, subscript and superscript are aligned horizontally to each other.
 When false, they are kerned to the shape of the base.
 Default value is false.
 
Example:
 
```php
  $baseElement = new MathematicalText("X");
  $subscript = new MathematicalText("i");
  $superscript = new MathematicalText("j");
  $subsuperscript = new MathRightSubSuperscriptElement($baseElement, $subscript, $superscript);
  $subsuperscript->setAlignScripts(true);
```


