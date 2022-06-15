---
title: removeUnusedLayoutSlides
type: docs
weight: 20
url: /php-java/compress/removeunusedlayoutslides/
---

# removeUnusedLayoutSlides(com.aspose.slides.Presentation) method

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

##  Parameters

| name | description |
| --- | --- |
| pres | The presentation instance |

##  Returns
Presentation


