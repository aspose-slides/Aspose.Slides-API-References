---
title: BrowsedAtKiosk
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/browsedatkiosk/browsedatkiosk/
---

## BrowsedAtKiosk()  constructor

 Initializes a new instance of the BrowsedAtKiosk class.
 

 
```php
  $pres = new Presentation();
  try {
    $pres->getSlideShowSettings()->setSlideShowType(new BrowsedAtKiosk());
    $pres->save("pres.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```


---


