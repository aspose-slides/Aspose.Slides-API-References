---
title: getEffective
type: docs
weight: 20
url: /php-java/textstyle/geteffective/
---

# getEffective() method

 Gets effective text style formatting data with the inheritance applied.
 

 This example demonstrates getting some of effective text style properties.
 
```php
  $pres = new Presentation("MyPresentation.pptx");
  try {
    $shape = $pres->getSlides()->get_Item(0)->getShapes()->get_Item(0);
    $effectiveTextStyle = $shape->getTextFrame()->getTextFrameFormat()->getTextStyle()->getEffective();
    for ($i = 0; $i < 8; $i++) {
      $effectiveStyleLevel = $effectiveTextStyle->getLevel($i);
      echo("= Effective paragraph formatting for style level #" + $i + " =");
      echo("Depth: " + $effectiveStyleLevel->getDepth());
      echo("Indent: " + $effectiveStyleLevel->getIndent());
      echo("Alignment: " + $effectiveStyleLevel->getAlignment());
      echo("Font alignment: " + $effectiveStyleLevel->getFontAlignment());
    }
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

##  Returns
A ITextStyleEffectiveData.


