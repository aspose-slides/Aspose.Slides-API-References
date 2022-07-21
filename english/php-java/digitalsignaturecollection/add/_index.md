---
title: add
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 20
url: /php-java/digitalsignaturecollection/add/
---

## add([DigitalSignature](../../digitalsignature) signature)  method

 Adds the signature at the end of collection.
 

 
```php
  $pres = new Presentation();
  try {
    $signature = new DigitalSignature("testsignature1.pfx", "testpass1");
    $signature->setComments("Aspose.Slides digital signing test.");
    $pres->getDigitalSignatures()->add($signature);
    $pres->save("SomePresentationSigned.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| signature | [DigitalSignature](../../digitalsignature) | Signature to add. |

### Returns
void


---


