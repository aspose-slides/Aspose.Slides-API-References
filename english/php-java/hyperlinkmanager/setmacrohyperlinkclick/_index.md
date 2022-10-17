---
title: setMacroHyperlinkClick
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 80
url: /php-java/hyperlinkmanager/setmacrohyperlinkclick/
---

## setMacroHyperlinkClick(String macroName)  method

 Set Macro hyperlink on a click.
 

 
```php
  $pres = new Presentation();
  try {
    $shape = $pres->getSlides()->get_Item(0)->getShapes()->addAutoShape(ShapeType.BlankButton, 20, 20, 80, 30);
    $shape->getHyperlinkManager()->setMacroHyperlinkClick("MacroName");
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| macroName | String | Name of the macro |

### Returns
[Hyperlink](../../hyperlink)


---


