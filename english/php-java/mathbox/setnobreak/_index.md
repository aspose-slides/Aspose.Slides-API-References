---
title: setNoBreak
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 130
url: /php-java/mathbox/setnobreak/
---

## setNoBreak(boolean value)  method

 No break
 This property specifies the "unbreakable" property on the object box. When true, no line breaks can occur within the box.
 This can be important for operator emulators that consist of more than one binary operator. 
 When this element is not specified, breaks can occur inside box.
 Default: true
 
Example:
 
```php
  $box = new MathBox(new MathematicalText("*****"));
  $box->setNoBreak(false);
```

### Returns
void


---


