---
title: getSlides
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 340
url: /php-java/presentation/getslides/
---

## getSlides()  method

 Returns a list of all slides that are defined in the presentation.
 Read-only  ISlideCollection.
 

 The following example shows how to set slides' background color of PowerPoint Presentation.
 
```php
  // Instantiate the Presentation class that represents the presentation file
  $pres = new Presentation();
  try {
    // Set the background color of the first ISlide to Blue
    $pres->getSlides()->get_Item(0)->getBackground()->setType(BackgroundType.OwnBackground);
    $pres->getSlides()->get_Item(0)->getBackground()->getFillFormat()->setFillType(FillType.Solid);
    $pres->getSlides()->get_Item(0)->getBackground()->getFillFormat()->getSolidFillColor()->setColor(Color::BLUE);
    $pres->save("ContentBG_out.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
[SlideCollection](../../slidecollection)


---


