---
title: getSlides
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 60
url: /php-java/slideshowsettings/getslides/
---

## getSlides()  method

 Slides range
 

 
```php
  $pres = new Presentation();
  try {
    $slidesRange = new SlidesRange();
    $slidesRange->setStart(1);
    $slidesRange->setEnd(3);
    $pres->getSlideShowSettings()->setSlides($slidesRange);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
SlidesRange


---


