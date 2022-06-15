---
title: deleteColumn
type: docs
weight: 20
url: /php-java/mathmatrix/deletecolumn/
---

# deleteColumn(int) method

 Deletes the specified column
 
Example:
 
```php
  $matrix = new MathMatrix(2, 3);
  $matrix->deleteColumn(0);
```

##  Parameters

| name | description |
| --- | --- |
| columnIndex | The zero-based index of the column to delete. |

##  Exception
ArgumentOutOfRangeException If columnIndex less than zero or greater or equal to the ColumnCount


