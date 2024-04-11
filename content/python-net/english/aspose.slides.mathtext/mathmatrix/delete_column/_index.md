---
title: delete_column method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/mathmatrix/delete_column/
weight: 310
---


## delete_column {#int}
Deletes the specified column


```python
def delete_column(self, column_index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| column_index | int | The zero-based index of the column to delete. |

## Exceptions

| Exception | Description |
| :- | :- |
| .NET type System.InvalidOperationException | When you try to delete the last single column in the matrix |
| .NET type System.ArgumentOutOfRangeException | If columnIndex less than zero or greater or equal to the ColumnCount |



