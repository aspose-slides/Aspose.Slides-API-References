---
title: getExportHiddenSlides
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 20
url: /php-java/xamloptions/getexporthiddenslides/
---

## getExportHiddenSlides() method

 Determines whether hidden slides will be exported.
 

 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $xamlOptions = new XamlOptions();
    $xamlOptions->setExportHiddenSlides(true);
    $pres->save($xamlOptions);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```


---


