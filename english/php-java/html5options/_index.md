---
title: Html5Options
type: docs
weight: 0
url: /php-java/html5options/
---

# Html5Options class

 Represents a HTML5 exporting options.
 
 Example:
 
```php
  $pres = new Presentation("demo.pptx");
  try {
    $htmlOptions = new Html5Options();
    $htmlOptions->setAnimateShapes(true);
    $htmlOptions->setAnimateTransitions(true);
    $pres->save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, $htmlOptions);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

## Constructors

| name | description |
| --- | --- |
| [Html5Options](/slides/php-java/html5options/html5options/)() |  |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getAnimateShapes](/slides/php-java/html5options/getanimateshapes/)() | boolean | Returns or sets shapes animation option. Read/write boolean. |
| [getAnimateTransitions](/slides/php-java/html5options/getanimatetransitions/)() | boolean | Returns or sets transitions animation option. Read/write boolean. |
| [setAnimateShapes](/slides/php-java/html5options/setanimateshapes/)(boolean) | void | Returns or sets shapes animation option. Read/write boolean. |
| [setAnimateTransitions](/slides/php-java/html5options/setanimatetransitions/)(boolean) | void | Returns or sets transitions animation option. Read/write boolean. |
