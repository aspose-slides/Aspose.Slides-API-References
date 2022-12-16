---
title: setAlignment
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 210
url: /php-java/paragraphformat/setalignment/
---

## setAlignment(int value)  method

 Returns or sets the text alignment in a paragraph with no inheritance.
 Read/write  TextAlignment.
 

 The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
 
```php
  // Instantiate a Presentation object that represents a PPTX file
  $pres = new Presentation("ParagraphsAlignment.pptx");
  try {
    // Accessing first slide
    $slide = $pres->getSlides()->get_Item(0);
    // Accessing the first and second placeholder in the slide and typecasting it as AutoShape
    $tf1 = $slide->getShapes()->get_Item(0)->getTextFrame();
    $tf2 = $slide->getShapes()->get_Item(1)->getTextFrame();
    // Change the text in both placeholders
    $tf1->setText("Center Align by Aspose");
    $tf2->setText("Center Align by Aspose");
    // Getting the first paragraph of the placeholders
    $para1 = $tf1->getParagraphs()->get_Item(0);
    $para2 = $tf2->getParagraphs()->get_Item(0);
    // Aligning the text paragraph to center
    $para1->getParagraphFormat()->setAlignment(TextAlignment.Center);
    $para2->getParagraphFormat()->setAlignment(TextAlignment.Center);
    // Writing the presentation as a PPTX file
    $pres->save("Centeralign_out.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
void


---


