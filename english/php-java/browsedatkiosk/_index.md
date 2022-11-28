---
title: BrowsedAtKiosk
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/browsedatkiosk/
---

## BrowsedAtKiosk class

 Browsed at a kiosk (full screen)
 

 
```php
  $pres = new Presentation();
  try {
    $pres->getSlideShowSettings()->setSlideShowType(new BrowsedAtKiosk());
    $pres->save("pres.pptx", SaveFormat::Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

## Constructors

| Name | Description |
| --- | --- |
| [BrowsedAtKiosk](browsedatkiosk)() | Initializes a new instance of the BrowsedAtKiosk class. |
