---
title: setExportHiddenSlides
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 80
url: /php-java/gifoptions/setexporthiddenslides/
---

## setExportHiddenSlides(boolean value)  method

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

### Returns
void


---


