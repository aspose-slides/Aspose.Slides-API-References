---
title: isValid
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 60
url: /php-java/digitalsignature/isvalid/
---

## isValid()  method

 If this digital signature is valid and the document has not been tampered with, this value will be true.
 Read-only  boolean.
 

 
```php
  $pres = new Presentation("SomePresentationSigned.pptx");
  try {
    for ($signature : $pres->getDigitalSignatures()) {
      echo("Signature check: " + $signature->isValid() ? "VALID" : "INVALID");
    }
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
boolean


---


