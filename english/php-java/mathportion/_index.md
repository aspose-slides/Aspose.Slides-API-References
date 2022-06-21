---
title: MathPortion
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/mathportion/
---

## MathPortion class

 Represents a portion with mathematical context inside.
 
Example:
 
```php
  $pres = new Presentation();
  try {
    $shape = $pres->getSlides()->get_Item(0)->getShapes()->addMathShape(0, 0, 300, 50);
    $paragraph = $shape->getTextFrame()->getParagraphs()->get_Item(0);
    $mathPortion = new MathPortion();
    $paragraph->getPortions()->add($mathPortion);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

## Constructors

| Name | Description |
| --- | --- |
| [MathPortion](mathportion)() | Initializes a new instance of the MathPortion class. |

## Methods

| Name | Description |
| --- | --- |
| [getMathParagraph](getmathparagraph)() | Math paragraph |
