---
title: removeUnusedMasterSlides
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 30
url: /php-java/compress/removeunusedmasterslides/
---

## removeUnusedMasterSlides(com.aspose.slides.Presentation) method

 Makes compression of the  Presentation by removing unused master slides.  
 

 
```php
  $pres = new Presentation("pres.pptx");
  try {
    Compress->removeUnusedMasterSlides($pres);
    $pres->save("pres-out.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| pres | The presentation instance |

### Returns
Presentation


---


