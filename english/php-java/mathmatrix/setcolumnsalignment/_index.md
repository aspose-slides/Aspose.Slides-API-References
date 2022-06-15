---
title: setColumnsAlignment
type: docs
weight: 250
url: /php-java/mathmatrix/setcolumnsalignment/
---

# setColumnsAlignment(int, long, int) method

 Set the horizontal alignment of the specified columns
 
Example:
 
```php
  $matrix = new MathMatrix(2, 3);
  $matrix->setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
```

##  Parameters

| name | description |
| --- | --- |
| columnIndex | Zero-based index of the first column to set alignment |
| columnsCount | The number of columns to specify the alignment |
| val | New value of horizontal alignment of specified column |


