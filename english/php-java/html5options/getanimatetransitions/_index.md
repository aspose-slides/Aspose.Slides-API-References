---
title: getAnimateTransitions
type: docs
weight: 30
url: /php-java/html5options/getanimatetransitions/
---

# getAnimateTransitions() method

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


