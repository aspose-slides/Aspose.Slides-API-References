---
title: getAnimateShapes
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 20
url: /php-java/html5options/getanimateshapes/
---

## getAnimateShapes()  method

 Returns or sets shapes animation option.
 Read/write  boolean.
 
 Example:
 
```php
  $pres = new Presentation("demo.pptx");
  try {
    $htmlOptions = new Html5Options();
    $htmlOptions->setAnimateShapes(true);
    $pres->save("demo-animate-shapes-and-transitions.html", SaveFormat::Html5, $htmlOptions);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
boolean


---


