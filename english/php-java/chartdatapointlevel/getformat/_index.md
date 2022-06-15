---
title: getFormat
type: docs
weight: 10
url: /php-java/chartdatapointlevel/getformat/
---

# getFormat() method

 Represents formatting properties of data point level.
 Read/write  IFormat.
 

 
```php
  $pres = new Presentation();
  try {
    $chart = $pres->getSlides()->get_Item(0)->getShapes()->addChart(ChartType.Treemap, 50, 50, 500, 400);
    $series = $chart->getChartData()->getSeries()->get_Item(0);
    $dataPointLevel = $series->getDataPoints()->get_Item(7)->getDataPointLevels()->get_Item(2);
    $dataPointLevel->getFormat()->getFill()->setFillType(FillType.Solid);
    $dataPointLevel->getFormat()->getFill()->getSolidFillColor()->setColor(Color::$Red);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

##  Returns
IFormat


