---
title: setAnimateTransitions
type: docs
weight: 50
url: /php-java/html5options/setanimatetransitions/
---

# setAnimateTransitions(boolean) method

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

##  Returns
boolean


