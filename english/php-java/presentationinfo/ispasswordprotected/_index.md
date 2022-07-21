---
title: isPasswordProtected
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 60
url: /php-java/presentationinfo/ispasswordprotected/
---

## isPasswordProtected()  method

 Gets a value that indicates whether a binded presentation is protected by a password to open.
 

 
```php
  $info = PresentationFactory->getInstance()->getPresentationInfo($presentationFilePath);
  if ($info->isPasswordProtected()) {
    echo("The presentation '" + $presentationFilePath + "' is protected by password to open.");
  }
```

### Returns
boolean


---


