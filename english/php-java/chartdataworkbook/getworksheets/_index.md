---
title: getWorksheets
type: docs
weight: 90
url: /php-java/chartdataworkbook/getworksheets/
---

# getWorksheets() method

 Gets a collection of worksheets.
 
 Example:
 
```php
  $pres = new Presentation();
  try {
    $chart = $pres->getSlides()->get_Item(0)->getShapes()->addChart(ChartType.Pie, 50, 50, 400, 500);
    $workbook = $chart->getChartData()->getChartDataWorkbook();
    for ($worksheet : $workbook->getWorksheets()) {
      $worksheetName = $worksheet->getName();
    }
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

