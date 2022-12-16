---
title: setExternalHyperlinkClick
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 40
url: /php-java/hyperlinkmanager/setexternalhyperlinkclick/
---

## setExternalHyperlinkClick(String url)  method

 Set external hyperlink on click.
 

 The following sample code shows how to add Text Box with Hyperlink.
 
```php
  // Instantiates a Presentation class that represents a PPTX
  $pres = new Presentation();
  try {
    // Gets the first slide in the presentation
    $slide = $pres->getSlides()->get_Item(0);
    // Adds an AutoShape object with type set as Rectangle
    $pptxShape = $slide->getShapes()->addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
    // Casts the shape to AutoShape
    $pptxAutoShape = $pptxShape;
    // Accesses the ITextFrame property associated with the AutoShape
    $pptxAutoShape->addTextFrame("");
    $textFrame = $pptxAutoShape->getTextFrame();
    $portion = $textFrame->getParagraphs()->get_Item(0)->getPortions()->get_Item(0);
    // Adds some text to the frame
    $portion->setText("Aspose.Slides");
    // Sets the Hyperlink for the portion text
    $hypMan = $portion->getPortionFormat()->getHyperlinkManager();
    $hypMan->setExternalHyperlinkClick("http://www.aspose.com");
    // Saves the PPTX Presentation
    $pres->save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| url | String | Hyperlink URL. |

### Returns
[Hyperlink](../../hyperlink)


---


