---
title: setRecoverWorkbookFromChartCache
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 70
url: /php-java/spreadsheetoptions/setrecoverworkbookfromchartcache/
---

## setRecoverWorkbookFromChartCache(boolean value)  method

  If data source for the chart is an external workbook and it's not available, it will be recovered from the chart cache.
  
 Example:
  
```php
  $spreadOptions = new SpreadsheetOptions();
  $spreadOptions->setRecoverWorkbookFromChartCache(true);
  $loadOptions = new LoadOptions();
  $loadOptions->setSpreadsheetOptions($spreadOptions);
  $pres = new Presentation("Presentation.pptx", $loadOptions);
  try {
    $chart = $pres->getSlides()->get_Item(0)->getShapes()->get_Item(0);
    $recoveredWorkbook = $chart->getChartData()->getChartDataWorkbook();
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
void

### Exception

| Exception | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when external workbook in unavailable and RecoverWorkbookFromChartCache property value is false. |


---


