---
title: ChartDataWorksheetCollection
type: docs
weight: 0
url: /php-java/chartdataworksheetcollection/
---

# ChartDataWorksheetCollection class

 Represents the collection of worksheets of chart data workbook.
 
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

## Methods

| name | return type | description |
| --- | --- | --- |
| [getSyncRoot](/php-java/chartdataworksheetcollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/php-java/chartdataworksheetcollection/get_item/)(int) | IChartDataWorksheet | Returns the worksheet by index. |
| [isSynchronized](/php-java/chartdataworksheetcollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/php-java/chartdataworksheetcollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/php-java/chartdataworksheetcollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [size](/php-java/chartdataworksheetcollection/size/)() | int | Returns the count. Read-only int. |
