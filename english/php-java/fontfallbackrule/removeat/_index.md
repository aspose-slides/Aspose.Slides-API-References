---
title: removeAt
type: docs
weight: 120
url: /php-java/fontfallbackrule/removeat/
---

# removeAt(int) method

 Removes the FallBack font at the specified index of the list.
 

 
```php
  // Create a rule contains a list of fonts.
  $newRule = new FontFallBackRule(0x3040, 0x309f, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
  // Removing Tahoma from the list.
  $newRule->remove(2);
```

##  Parameters

| name | description |
| --- | --- |
| index | The zero-based index of the font to remove. |


