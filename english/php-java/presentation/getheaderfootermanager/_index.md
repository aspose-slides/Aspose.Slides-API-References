---
title: getHeaderFooterManager
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 180
url: /php-java/presentation/getheaderfootermanager/
---

## getHeaderFooterManager()  method

 Returns actual HeaderFooter manager.
 Read-only  IPresentationHeaderFooterManager.
 

 The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
 
```php
  $pres = new Presentation("presentation.ppt");
  try {
    $headerFooterManager = $pres->getSlides()->get_Item(0)->getHeaderFooterManager();
    // Property IsFooterVisible is used for indicating that a slide footer placeholder is not present.
    if (!$headerFooterManager->isFooterVisible()) {
      $headerFooterManager->setFooterVisibility(true);// Method SetFooterVisibility is used for making a slide footer placeholder visible.

    }
    // Property IsSlideNumberVisible is used for indicating that a slide page number placeholder is not present.
    if (!$headerFooterManager->isSlideNumberVisible()) {
      $headerFooterManager->setSlideNumberVisibility(true);// Method SetSlideNumberVisibility is used for making a slide page number placeholder visible.

    }
    // Property IsDateTimeVisible is used for indicating that a slide date-time placeholder is not present.
    if (!$headerFooterManager->isDateTimeVisible()) {
      $headerFooterManager->setDateTimeVisibility(true);// Method SetFooterVisibility is used for making a slide date-time placeholder visible.

    }
    $headerFooterManager->setFooterText("Footer text");// Method SetFooterText is used for setting text to slide footer placeholder.

    $headerFooterManager->setDateTimeText("Date and time text");// Method SetDateTimeText is used for setting text to slide date-time placeholder.

    $pres->save("Presentation.ppt", SaveFormat.Ppt);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
[PresentationHeaderFooterManager](../../presentationheaderfootermanager)


---


