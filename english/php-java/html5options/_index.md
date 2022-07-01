---
title: Html5Options
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/html5options/
---

## Html5Options class

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

| Name | Description |
| --- | --- |
| [Html5Options](html5options)() |  |

## Methods

| Name | Description |
| --- | --- |
| [getAnimateShapes](getanimateshapes)() | Returns or sets shapes animation option. Read/write boolean. |
| [getAnimateTransitions](getanimatetransitions)() | Returns or sets transitions animation option. Read/write boolean. |
| [setAnimateShapes](setanimateshapes)(boolean) | Returns or sets shapes animation option. Read/write boolean. |
| [setAnimateTransitions](setanimatetransitions)(boolean) | Returns or sets transitions animation option. Read/write boolean. |
