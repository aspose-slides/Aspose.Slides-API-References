---
title: getSignTime
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 50
url: /php-java/digitalsignature/getsigntime/
---

## getSignTime()  method

 The time when the document was signed.
 Read-only  java.util.Date.
 

 
```php
  $pres = new Presentation("SomePresentationSigned.pptx");
  try {
    for ($signature : $pres->getDigitalSignatures()) {
      echo("Signature check: " + $signature->isValid() ? "VALID" : "INVALID" + ", Signing time: " + $signature->getSignTime());
    }
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
java.util.Date


---


