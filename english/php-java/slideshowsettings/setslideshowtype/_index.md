---
title: setSlideShowType
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 110
url: /php-java/slideshowsettings/setslideshowtype/
---

## setSlideShowType([SlideShowType](../../slideshowtype) value)  method

 Gets or sets the slide show type. Represented by the following  SlideShowType( #getSlideShowType/ #setSlideShowType(SlideShowType)) ancestors:  BrowsedAtKiosk,  PresentedBySpeaker and  BrowsedByIndividual 
 

 
```php
  $pres = new Presentation();
  try {
    // to set "Browsed at a kiosk (full screen)" type
    $pres->getSlideShowSettings()->setSlideShowType(new BrowsedAtKiosk());
    // to set "Browsed by individual (window)" type
    $pres->getSlideShowSettings()->setSlideShowType(new BrowsedByIndividual());
    // to set "Presented by a speaker (full screen)" type
    $pres->getSlideShowSettings()->setSlideShowType(new PresentedBySpeaker());
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
void


---


