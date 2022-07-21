---
title: getDigitalSignatures
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 260
url: /php-java/presentation/getdigitalsignatures/
---

## getDigitalSignatures()  method

 Returns the collection of signatures used to sign the presentation.
 Read-only  IDigitalSignatureCollection.
 

 
```php
  $pres = new Presentation("SomePresentationSigned.pptx");
  try {
    if ($pres->getDigitalSignatures()->size() > 0) {
      $allSignaturesAreValid = true;
      echo("Signatures used to sign the presentation: ");
      for ($signature : $pres->getDigitalSignatures()) {
        echo($signature->getCertificate()->hashCode() + ", " + $signature->getSignTime()->toString() + " -- " + $signature->isValid() ? "VALID" : "INVALID");
        $allSignaturesAreValid = $signature->isValid();
      }
      if ($allSignaturesAreValid) {
        echo("Presentation is genuine, all signatures are valid.");
      } else {
        echo("Presentation has been modified since signing.");
      }
    }
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
[DigitalSignatureCollection](../../digitalsignaturecollection)


---


