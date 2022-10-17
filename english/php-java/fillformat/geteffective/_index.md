---
title: getEffective
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/fillformat/geteffective/
---

## getEffective()  method

 Gets effective fill formatting data with the inheritance applied.
 

 This example demonstrates getting shape's effective fill format properties.
 
```php
  $pres = new Presentation("MyPresentation.pptx");
  try {
    $effectiveFillFormat = $pres->getSlides()->get_Item(0)->getShapes()->get_Item(0)->getFillFormat()->getEffective();
    echo("Type: " + $effectiveFillFormat->getFillType());
    switch ($effectiveFillFormat->getFillType()) {
      case FillType::Solid :
        echo("Fill color: " + $effectiveFillFormat->getSolidFillColor());
        break;
      case FillType::Pattern :
        echo("Pattern style: " + $effectiveFillFormat->getPatternFormat()->getPatternStyle());
        echo("Fore color: " + $effectiveFillFormat->getPatternFormat()->getForeColor());
        echo("Back color: " + $effectiveFillFormat->getPatternFormat()->getBackColor());
        break;
      case FillType::Gradient :
        echo("Gradient direction: " + $effectiveFillFormat->getGradientFormat()->getGradientDirection());
        echo("Gradient stops count: " + $effectiveFillFormat->getGradientFormat()->getGradientStops()->size());
        break;
      case FillType::Picture :
        echo("Picture width: " + $effectiveFillFormat->getPictureFillFormat()->getPicture()->getImage()->getWidth());
        echo("Picture height: " + $effectiveFillFormat->getPictureFillFormat()->getPicture()->getImage()->getHeight());
        break;
    }
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
FillFormatEffectiveData


---


