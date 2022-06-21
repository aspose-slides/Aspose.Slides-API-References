---
title: getRecoverWorkbookFromChartCache
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 30
url: /php-java/spreadsheetoptions/getrecoverworkbookfromchartcache/
---

## getRecoverWorkbookFromChartCache() method

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

### Exception

| Exception | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when external workbook in unavailable and RecoverWorkbookFromChartCache property value is false. |


---


