---
title: removeUnusedLayoutSlides
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 30
url: /php-java/compress/removeunusedlayoutslides/
---

## removeUnusedLayoutSlides([Presentation](../../presentation) pres)  method

 Makes compression of the  Presentation by removing unused layout slides.  
 

 
```php
  $pres = new Presentation("pres.pptx");
  try {
    Compress->removeUnusedLayoutSlides($pres);
    $pres->save("pres-out.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../presentation) | The presentation instance |

### Returns
void


---


