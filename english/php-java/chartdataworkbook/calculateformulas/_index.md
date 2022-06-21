---
title: calculateFormulas
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/chartdataworkbook/calculateformulas/
---

## calculateFormulas() method

  Calculates all formulas in the workbook and updates corresponding cells values. 
  

  Example shows how to assign a formula to the cell and to calculate a value. The value of the "B4" cell is getting set to 5.
  
```php
  $pres = new Presentation();
  try {
    $chart = $pres->getSlides()->get_Item(0)->getShapes()->addChart(ChartType.Pie, 100, 100, 300, 400);
    $wb = $chart->getChartData()->getChartDataWorkbook();
    $wb->getCell(0, "B2", 2);
    $wb->getCell(0, "B3", 3);
    $wb->getCell(0, "B4")->setFormula("B2+B3");
    $wb->calculateFormulas();
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Exception

| Exception | Condition |
| --- | --- |
 | CellUnsupportedDataException | Cell data is not supported. |


---


