---
title: deleteColumn
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 20
url: /php-java/mathmatrix/deletecolumn/
---

## deleteColumn(int columnIndex)  method

 Deletes the specified column
 
Example:
 
```php
  $matrix = new MathMatrix(2, 3);
  $matrix->deleteColumn(0);
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| columnIndex | int | The zero-based index of the column to delete. |

### Returns
void

### Exception

| Exception | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | If columnIndex less than zero or greater or equal to the ColumnCount |


---


