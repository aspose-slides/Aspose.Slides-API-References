---
title: addDataPointForMapSeries
type: docs
weight: 240
url: /php-java/chartdatapointcollection/adddatapointformapseries/
---

# addDataPointForMapSeries(com.aspose.slides.IChartDataCell) method

  Creates the new data point and adds it to the end of collection.
  Applicable for series which chart type is Map.
  

  
```php
  $pres = new Presentation();
  try {
    $chart = $pres->getSlides()->get_Item(0)->getShapes()->addChart(ChartType.Map, 50, 50, 500, 400, false);
    $wb = $chart->getChartData()->getChartDataWorkbook();
    $series = $chart->getChartData()->getSeries()->add(ChartType.Map);
    $series->getDataPoints()->addDataPointForMapSeries($wb->getCell(0, "B2", 5));
    $series->getDataPoints()->addDataPointForMapSeries($wb->getCell(0, "B3", 1));
    $series->getDataPoints()->addDataPointForMapSeries($wb->getCell(0, "B4", 10));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

##  Parameters

| name | description |
| --- | --- |
| value | Data point ColorValue |

##  Returns
New data point.

