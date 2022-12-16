---
title: getAllCustomXmlParts
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 80
url: /php-java/presentation/getallcustomxmlparts/
---

## getAllCustomXmlParts()  method

 Returns all custom data parts in the presentaion.
 Read-only  ICustomXmlPart[].
 

 The following examples show how to clear all custom xml parts from PowerPoint Presentation.
 
```php
  $pres = new Presentation("PresentationWithCustomXml.pptx");
  try {
    // Iterate all custom XML Parts
    for ($item : $pres->getAllCustomXmlParts()) {
      $item->remove();
    }
    $pres->save("out.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
[CustomXmlPart](../../customxmlpart)


---


