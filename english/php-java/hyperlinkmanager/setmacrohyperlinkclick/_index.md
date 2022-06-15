---
title: setMacroHyperlinkClick
type: docs
weight: 80
url: /php-java/hyperlinkmanager/setmacrohyperlinkclick/
---

# setMacroHyperlinkClick(java.lang.String) method

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

##  Parameters

| name | description |
| --- | --- |
| macroName | Name of the macro |

##  Returns
Hyperlink object IHyperlink


