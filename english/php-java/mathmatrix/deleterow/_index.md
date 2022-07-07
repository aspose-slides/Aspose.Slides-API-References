---
title: deleteRow
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 30
url: /php-java/mathmatrix/deleterow/
---

## deleteRow(int rowIndex)  method

 Deletes the specified row
 
Example:
 
```php
  $matrix = new MathMatrix(2, 3);
  $matrix->deleteRow(0);
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| rowIndex | int | The zero-based index of the row to delete. |

### Exception

| Exception | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | If rowIndex less than zero or greater or equal to the RowCount |


---


