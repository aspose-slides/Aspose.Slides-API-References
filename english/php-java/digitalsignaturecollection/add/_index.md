---
title: add
type: docs
weight: 10
url: /php-java/digitalsignaturecollection/add/
---

# add(com.aspose.slides.IDigitalSignature) method

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

##  Parameters

| name | description |
| --- | --- |
| signature | Signature to add. |


