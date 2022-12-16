---
title: highlightText
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 90
url: /php-java/textframe/highlighttext/
---

## highlightText(String text, Color highlightColor)  method

 Highlight all matches of sample in text frame text using specified color.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| text | String | Text sample to highlight. |
| highlightColor | Color | Highlighting color. |

### Returns
void


---


## highlightText(String text, Color highlightColor, [TextHighlightingOptions](../../texthighlightingoptions) options)  method

 Highlight all matches of sample in text frame text using specified color.
 

 The following sample code shows how to Highlight Text in a PowerPoint Presentation.
 
```php
  try {
    $textHighlightingOptions = new TextHighlightingOptions();
    $textHighlightingOptions->setWholeWordsOnly(true);
    // highlighting all words 'important'
    $pres->getSlides()->get_Item(0)->getShapes()->get_Item(0)->getTextFrame()->highlightText("title", Color::BLUE);
    // highlighting all separate 'the' occurrences
    $pres->getSlides()->get_Item(0)->getShapes()->get_Item(0)->getTextFrame()->highlightText("to", Color::MAGENTA, $textHighlightingOptions);
    $pres->save("SomePresentation-out2.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| text | String | Text sample to highlight. |
| highlightColor | Color | Highlighting color. |
| options | [TextHighlightingOptions](../../texthighlightingoptions) | Highlighting options. |

### Returns
void


---


