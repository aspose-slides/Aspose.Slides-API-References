---
title: getRange
type: docs
weight: 50
url: /php-java/chartdata/getrange/
---

# getRange() method

  Gets chart data range.
  

  
```php
  $pres = new Presentation();
  try {
    $chart = $pres->getSlides()->get_Item(0)->getShapes()->addChart(ChartType.PercentsStackedBar, 0, 0, 100, 100);
    $result = $chart->getChartData()->getRange();
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

##  Returns
Cells data range formula. E.g: "Sheet1!$A$1:$C$4"

##  Exception
InvalidOperationException Chart doesn't use workbook as a data source


