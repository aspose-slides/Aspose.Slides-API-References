---
title: setExportHiddenSlides
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 70
url: /php-java/gifoptions/setexporthiddenslides/
---

## setExportHiddenSlides(boolean) method

 Determines whether hidden slides will be exported.
 The default value is false. 
 

 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $gifOptions = new GifOptions();
    $gifOptions->setExportHiddenSlides(false);
    $pres->save("pres.gif", SaveFormat.Gif, $gifOptions);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```


---


