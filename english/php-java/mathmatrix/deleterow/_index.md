---
title: deleteRow
type: docs
weight: 30
url: /php-java/mathmatrix/deleterow/
---

# deleteRow(int) method

 Deletes the specified row
 
Example:
 
```php
  $matrix = new MathMatrix(2, 3);
  $matrix->deleteRow(0);
```

##  Parameters

| name | description |
| --- | --- |
| rowIndex | The zero-based index of the row to delete. |

##  Exception
ArgumentOutOfRangeException If rowIndex less than zero or greater or equal to the RowCount


