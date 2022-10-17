---
title: BrowsedByIndividual
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/browsedbyindividual/
---

## BrowsedByIndividual class

 Browsed by individual (window)
 

 
```php
  $pres = new Presentation();
  try {
    $pres->getSlideShowSettings()->setSlideShowType(new BrowsedByIndividual());
    $pres->save("pres.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

## Constructors

| Name | Description |
| --- | --- |
| [BrowsedByIndividual](browsedbyindividual)() | Initializes a new instance of the BrowsedByIndividual class. |

## Methods

| Name | Description |
| --- | --- |
| [getShowScrollbar](getshowscrollbar)() | Show Scroll Bar in Window |
| [setShowScrollbar](setshowscrollbar)(boolean) | Show Scroll Bar in Window |
