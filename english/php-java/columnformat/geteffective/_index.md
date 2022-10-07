---
title: getEffective
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/columnformat/geteffective/
---

## getEffective()  method

 Gets effective table column formatting properties with inheritance and table styles applied.
 

 This example demonstrates getting effective fill format for different table logic parts.
 Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
 So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
 
```php
  $pres = new Presentation("MyPresentation.pptx");
  try {
    $tbl = $pres->getSlides()->get_Item(0)->getShapes()->get_Item(0);
    $tableFillFormatEffective = $tbl->getTableFormat()->getEffective()->getFillFormat();
    $rowFillFormatEffective = $tbl->getRows()->get_Item(0)->getRowFormat()->getEffective()->getFillFormat();
    $columnFillFormatEffective = $tbl->getColumns()->get_Item(0)->getColumnFormat()->getEffective()->getFillFormat();
    $cellFillFormatEffective = $tbl->get_Item(0, 0)->getCellFormat()->getEffective()->getFillFormat();
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
ColumnFormatEffectiveData


---


