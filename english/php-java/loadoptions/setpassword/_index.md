---
title: setPassword
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 230
url: /php-java/loadoptions/setpassword/
---

## setPassword(String value)  method

 Gets or sets the password.
 Read/write  String.
 Value: 
 The password.

 The following sample code shows how to open password protected PowerPoint Presentation.
 
```php
  $loadOptions = new LoadOptions();
  $loadOptions->setPassword("YOUR_PASSWORD");
  $pres = new Presentation("pres.pptx", $loadOptions);
  try {
    // work with decrypted presentation
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
void


---


