---
title: removeUnusedMasterSlides
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 40
url: /php-java/compress/removeunusedmasterslides/
---

## removeUnusedMasterSlides([Presentation](../../presentation) pres)  method

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

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../presentation) | The presentation instance |

### Returns
void


---


