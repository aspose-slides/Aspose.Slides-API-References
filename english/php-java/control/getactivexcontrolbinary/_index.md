---
title: getActiveXControlBinary
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 30
url: /php-java/control/getactivexcontrolbinary/
---

## getActiveXControlBinary()  method

 Specifies the persistence of an ActiveX control when the method used to persist is either PersistStream, PersistStreamInit or PersistStorage.
 

 Next example shows the using ActiveXControlBinary property for changing ActiveX properties:
 
```php
  if ($control->getPersistence() == PersistenceType::PersistPropertyBag) {
    $control->getProperties()->set_Item("Value", $value);
  } else {
    YourMethodHere($control->getActiveXControlBinary());// Use your own method for managing ActiveX properties stored in its binary file

  }
```

### Returns
OrderedDictionary, Hashtable, LinkedList


---


