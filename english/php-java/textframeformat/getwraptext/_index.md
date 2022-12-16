---
title: getWrapText
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 180
url: /php-java/textframeformat/getwraptext/
---

## getWrapText()  method

 True if text is wrapped at TextFrame's margins.
 Read/write  NullableBool.
 

 The following sample code shows how to wrap text in Presentation.
 
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
    $textFrameFormat->setWrapText(NullableBool.True);
    $pres->save("Output-presentation.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
OrderedDictionary, Hashtable, LinkedList


---


