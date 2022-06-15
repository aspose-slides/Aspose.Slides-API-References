---
title: setTargetSection
type: docs
weight: 20
url: /php-java/sectionzoomframe/settargetsection/
---

# setTargetSection(com.aspose.slides.ISection) method

 Gets or sets the section object that the Section Zoom object links to.
 Read/write  ISection.
 
Next example demonstrates changing target section and creates new image for the section zoom object:
 
```php
  $pres = new Presentation();
  try {
    $sectionZoomFrame = $pres->getSlides()->get_Item(0)->getShapes()->addSectionZoomFrame(150, 20, 50, 50, $pres->getSections()->get_Item(1));
    $sectionZoomFrame->setTargetSection($pres->getSections()->get_Item(2));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

##  Returns
ISection


