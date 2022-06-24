---
title: setExportHiddenSlides
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 40
url: /php-java/xamloptions/setexporthiddenslides/
---

## setExportHiddenSlides(boolean) method

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


