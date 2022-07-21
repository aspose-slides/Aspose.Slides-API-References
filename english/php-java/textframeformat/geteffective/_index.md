---
title: getEffective
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 180
url: /php-java/textframeformat/geteffective/
---

## getEffective()  method

 Gets effective text frame formatting data with the inheritance applied.
 

 This example demonstrates getting some of effective text frame formatting properties.
 
```php
  $pres = new Presentation("MyPresentation.pptx");
  try {
    $shape = $pres->getSlides()->get_Item(0)->getShapes()->get_Item(0);
    $effectiveTextFrameFormat = $shape->getTextFrame()->getTextFrameFormat()->getEffective();
    echo("Anchoring type: " + $effectiveTextFrameFormat->getAnchoringType());
    echo("Autofit type: " + $effectiveTextFrameFormat->getAutofitType());
    echo("Text vertical type: " + $effectiveTextFrameFormat->getTextVerticalType());
    echo("Margins");
    echo("   Left: " + $effectiveTextFrameFormat->getMarginLeft());
    echo("   Top: " + $effectiveTextFrameFormat->getMarginTop());
    echo("   Right: " + $effectiveTextFrameFormat->getMarginRight());
    echo("   Bottom: " + $effectiveTextFrameFormat->getMarginBottom());
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
[TextFrameFormatEffectiveData](../../textframeformateffectivedata)


---


