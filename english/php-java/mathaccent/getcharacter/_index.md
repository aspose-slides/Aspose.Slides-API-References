---
title: getCharacter
type: docs
weight: 40
url: /php-java/mathaccent/getcharacter/
---

# getCharacter() method

 Accent Character
 The value should be within the range of (U+0300–U+036F) or(U+20D0–U+20EF)
 Default value: Combining Circumflex Accent (U+0302)
 
Example:
 
```php
  $accent = new MathematicalText("x")->accent('~');
  $ch = $accent->getCharacter();
```


