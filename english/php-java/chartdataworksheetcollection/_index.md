---
title: ChartDataWorksheetCollection
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/chartdataworksheetcollection/
---

## ChartDataWorksheetCollection class

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

| Name | Description |
| --- | --- |
| [getSyncRoot](getsyncroot)() | Returns a synchronization root. Read-only Object. |
| [get_Item](get_item)(int) | Returns the worksheet by index. |
| [isSynchronized](issynchronized)() | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](iterator)() | Returns an enumerator that iterates through the collection. |
| [iteratorJava](iteratorjava)() | Returns a java iterator for the entire collection. |
| [size](size)() | Returns the count. Read-only int. |
