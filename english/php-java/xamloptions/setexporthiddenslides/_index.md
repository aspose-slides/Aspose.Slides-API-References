---
title: setExportHiddenSlides
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 220
url: /php-java/xamloptions/setexporthiddenslides/
---

## setExportHiddenSlides(boolean value)  method

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

### Returns
void


---


