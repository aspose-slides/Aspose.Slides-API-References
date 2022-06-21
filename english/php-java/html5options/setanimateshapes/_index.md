---
title: setAnimateShapes
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 40
url: /php-java/html5options/setanimateshapes/
---

## setAnimateShapes(boolean) method

 Returns or sets shapes animation option.
 Read/write  boolean.
 
 Example:
 
```php
  $pres = new Presentation("demo.pptx");
  try {
    $htmlOptions = new Html5Options();
    $htmlOptions->setAnimateShapes(true);
    $pres->save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, $htmlOptions);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
boolean


---


