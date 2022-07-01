---
title: setAnimateTransitions
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 50
url: /php-java/html5options/setanimatetransitions/
---

## setAnimateTransitions(boolean value)  method

 Returns or sets transitions animation option.
 Read/write  boolean.
 
 Example:
 
```php
  $pres = new Presentation("demo.pptx");
  try {
    $htmlOptions = new Html5Options();
    $htmlOptions->setAnimateTransitions(true);
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


