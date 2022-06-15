---
title: getLabel
type: docs
weight: 20
url: /php-java/chartdatapointlevel/getlabel/
---

# getLabel() method

 Represents data label of data point level. Applied for Treemap and  Sunburst sereis types.
 Read-only  IDataLabel.
 

 
```php
  $pres = new Presentation();
  try {
    $chart = $pres->getSlides()->get_Item(0)->getShapes()->addChart(ChartType.Sunburst, 50, 50, 500, 400);
    $series = $chart->getChartData()->getSeries()->get_Item(0);
    $dataPointLevel = $series->getDataPoints()->get_Item(0)->getDataPointLevels()->get_Item(1);
    $dataPointLevel->getLabel()->getDataLabelFormat()->setShowCategoryName(false);
    $dataPointLevel->getLabel()->getDataLabelFormat()->setShowValue(true);
    $dataPointLevel->getLabel()->getDataLabelFormat()->setShowSeriesName(true);
    $dataPointLevel = $series->getDataPoints()->get_Item(12)->getDataPointLevels()->get_Item(1);
    $dataPointLevel->getLabel()->getTextFormat()->getPortionFormat()->getFillFormat()->setFillType(FillType.Solid);
    $dataPointLevel->getLabel()->getTextFormat()->getPortionFormat()->getFillFormat()->getSolidFillColor()->setColor(Color::$Red);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

##  Returns
IDataLabel


