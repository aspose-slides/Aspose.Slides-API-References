---
title: setExternalWorkbook
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 160
url: /php-java/chartdata/setexternalworkbook/
---

## setExternalWorkbook(String workbookPath)  method

 Sets external workbook as a data source for the chart. Chart data will be updated from the target workbook.  
 

 
```php
  $pres = new Presentation();
  try {
    $chart = $pres->getSlides()->get_Item(0)->getShapes()->addChart(ChartType.Pie, 50, 50, 400, 600, true);
    $chartData = $chart->getChartData();
    $chartData->setExternalWorkbook("../../workbook.xlsx");
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| workbookPath | String | Path to the target workbook |

### Returns
void

### Exception

| Exception | Condition |
| --- | --- |
 | InvalidOperationException | External workbook is not available or can't be loaded. |


---


## setExternalWorkbook(String workbookPath, boolean updateChartData)  method

 Sets external workbook as a data source for the chart. 
 

 
```php
  $pres = new Presentation();
  try {
    $chart = $pres->getSlides()->get_Item(0)->getShapes()->addChart(ChartType.Pie, 50, 50, 400, 600, true);
    $chartData = $chart->getChartData();
    ChartData->setExternalWorkbook("http://path/doesnt/exists", false) = $missing$;
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| workbookPath | String | Path to the target workbook |
| updateChartData | boolean | If value is false only workbook path will be updated. Chart data won't be loaded and updated from the target workbook. Can be used when target workbook doesn't exist or it's not available. If value is true chart data will be updated from the target workbook. |

### Returns
void

### Exception

| Exception | Condition |
| --- | --- |
 | InvalidOperationException | External workbook is not available or can't be loaded. |


---


