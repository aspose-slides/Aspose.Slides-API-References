---
title: highlightRegex
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 80
url: /php-java/textframe/highlightregex/
---

## highlightRegex(String regex, Color highlightColor, [TextHighlightingOptions](../../texthighlightingoptions) options)  method

 Highlight all matches of regular expression in text frame text using specified color.
 

 The following sample code shows how to Highlight Text using regular expression in a PowerPoint Presentation.
 
```php
  $pres = new Presentation("SomePresentation.pptx");
  try {
    $options = new TextHighlightingOptions();
    // highlighting all words with 10 symbols or longer
    $pres->getSlides()->get_Item(0)->getShapes()->get_Item(0)->getTextFrame()->highlightRegex("\\b[^\\s){5,}\\b", Color::BLUE, $options);
    $pres->save("SomePresentation-out.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| regex | String | Text of regular expression to get text to highlight. |
| highlightColor | Color | Highlighting color. |
| options | [TextHighlightingOptions](../../texthighlightingoptions) | Highlighting options. |

### Returns
void


---


