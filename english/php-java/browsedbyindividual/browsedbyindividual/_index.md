---
title: BrowsedByIndividual
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/browsedbyindividual/browsedbyindividual/
---

## BrowsedByIndividual()  constructor

 Initializes a new instance of the BrowsedByIndividual class.
 

 
```php
  $pres = new Presentation();
  try {
    $pres->getSlideShowSettings()->setSlideShowType(new BrowsedByIndividual());
    $pres->save("pres.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```


---


