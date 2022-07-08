---
title: setOperatorEmulator
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 140
url: /php-java/mathbox/setoperatoremulator/
---

## setOperatorEmulator(boolean value)  method

 Operator Emulator.
 When true, the box and its contents behave as a single operator and inherit the properties of an operator. 
 This means, for example, that the character can serve as a point for a line break and can be aligned to other operators.
 Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='.
 Default value: false
 
Example:
 
```php
  $box = new MathBox(new MathematicalText("=="));
  $box->setOperatorEmulator(true);
```

### Returns
void


---


