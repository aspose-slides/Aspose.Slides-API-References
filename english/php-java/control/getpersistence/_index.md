---
title: getPersistence
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 100
url: /php-java/control/getpersistence/
---

## getPersistence()  method

 Gets the method used to store properties of the ActiveX control.
 Read only  PersistenceType.
 

 Next example shows the using Persistence property for checking if properties of ActiveX object may be changed as XML based ActiveX properties:
 
```php
  if ($control->getPersistence() == PersistenceType::PersistPropertyBag) {
    $control->getProperties()->set_Item("Value", $value);
  } else {
    YourMethodHere($control->getActiveXControlBinary());// Use your own method for managing ActiveX properties stored in its binary file

  }
```

### Returns
int


---


