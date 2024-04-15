---
title: delete_row method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---


## delete_row {#int}
Deletes the specified row


```python
def delete_row(self, row_index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| row_index | int | The zero-based index of the row to delete. |

## Exceptions

| Exception | Description |
| :- | :- |
| **System.InvalidOperationException** | When you try to delete the last single row in the matrix |
| **System.ArgumentOutOfRangeException** | If rowIndex less than zero or greater or equal to the RowCount |



### See Also
* class [`MathMatrix`](/slides/python-net/aspose.slides.mathtext/mathmatrix)
* module [`aspose.slides.mathtext`](/slides/python-net/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)
