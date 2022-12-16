---
title: setAutofitType
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 200
url: /php-java/textframeformat/setautofittype/
---

## setAutofitType(OrderedDictionary value)  method

 Returns or sets text's autofit mode.
 Read/write  TextAutofitType.
 

 The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
 
```php
  $pres = new Presentation();
  try {
    $slide = $pres->getSlides()->get_Item(0);
    $autoShape = $slide->getShapes()->addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
    $portion = new Portion("lorem ipsum...");
    $portion->getPortionFormat()->getFillFormat()->getSolidFillColor()->setColor(Color::BLACK);
    $portion->getPortionFormat()->getFillFormat()->setFillType(FillType.Solid);
    $autoShape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->add($portion);
    $textFrameFormat = $autoShape->getTextFrame()->getTextFrameFormat();
    $textFrameFormat->setAutofitType(TextAutofitType.Shape);
    $pres->save("Output-presentation.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
void


---


## setAutofitType(Hashtable value)  method

 Returns or sets text's autofit mode.
 Read/write  TextAutofitType.
 

 The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
 
```php
  $pres = new Presentation();
  try {
    $slide = $pres->getSlides()->get_Item(0);
    $autoShape = $slide->getShapes()->addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
    $portion = new Portion("lorem ipsum...");
    $portion->getPortionFormat()->getFillFormat()->getSolidFillColor()->setColor(Color::BLACK);
    $portion->getPortionFormat()->getFillFormat()->setFillType(FillType.Solid);
    $autoShape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->add($portion);
    $textFrameFormat = $autoShape->getTextFrame()->getTextFrameFormat();
    $textFrameFormat->setAutofitType(TextAutofitType.Shape);
    $pres->save("Output-presentation.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
void


---


## setAutofitType(LinkedList value)  method

 Returns or sets text's autofit mode.
 Read/write  TextAutofitType.
 

 The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
 
```php
  $pres = new Presentation();
  try {
    $slide = $pres->getSlides()->get_Item(0);
    $autoShape = $slide->getShapes()->addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
    $portion = new Portion("lorem ipsum...");
    $portion->getPortionFormat()->getFillFormat()->getSolidFillColor()->setColor(Color::BLACK);
    $portion->getPortionFormat()->getFillFormat()->setFillType(FillType.Solid);
    $autoShape->getTextFrame()->getParagraphs()->get_Item(0)->getPortions()->add($portion);
    $textFrameFormat = $autoShape->getTextFrame()->getTextFrameFormat();
    $textFrameFormat->setAutofitType(TextAutofitType.Shape);
    $pres->save("Output-presentation.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
void


---


