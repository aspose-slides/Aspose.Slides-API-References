---
title: isWriteProtected
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 70
url: /php-java/presentationinfo/iswriteprotected/
---

## isWriteProtected()  method

 Gets a value that indicates whether a binded presentation is write protected.
 
 If the presentation is protected by a password to open, the property value equals NotDefined.
 

 
```php
  $info = PresentationFactory->getInstance()->getPresentationInfo($presentationFilePath);
  if ($info->isWriteProtected() == NullableBool::True) {
    echo("The presentation '" + $presentationFilePath + "' is protected by password to open.");
  }
```

### Returns
OrderedDictionary, Hashtable, LinkedList


---


