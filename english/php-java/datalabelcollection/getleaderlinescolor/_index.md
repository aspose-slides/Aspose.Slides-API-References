---
title: getLeaderLinesColor
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 50
url: /php-java/datalabelcollection/getleaderlinescolor/
---

## getLeaderLinesColor()  method

 Gets or sets the color of all leader lines in the collection.
 Read/write  java.awt.Color.
 
Example:
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $chart = $pres->getSlides()->get_Item(0)->getShapes()->get_Item(0);
    $series = $chart->getChartData()->getSeries();
    $labels = $series->get_Item(0)->getLabels();
    $labels->setLeaderLinesColor(Color::RED);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
Color


---


