---
title: getEffective
type: docs
weight: 20
url: /php-java/background/geteffective/
---

# getEffective() method

 Gets effective background data with the inheritance applied.
 

 This example demonstrates getting effective background properties.
 
```php
  $pres = new Presentation("MyPresentation.pptx");
  try {
    $effectiveBackground = $pres->getSlides()->get_Item(0)->getBackground()->getEffective();
    echo("Background fill type: " + $effectiveBackground->getFillFormat()->getFillType());
    echo("Any effects applied: " + !$effectiveBackground->getEffectFormat()->isNoEffects());
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

##  Returns
A IBackgroundEffectiveData.

