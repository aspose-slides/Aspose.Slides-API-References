﻿---
title: delete_column method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---


## delete_column {#int}
Deletes the specified column


```python
def delete_column(self, column_index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| column_index | **int** | The zero-based index of the column to delete. |

### Examples

Example:

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | When you try to delete the last single column in the matrix |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | If columnIndex less than zero or greater or equal to the ColumnCount |



### See Also
* class [`MathMatrix`](/slides/python-net/aspose.slides.mathtext/mathmatrix)
* module [`aspose.slides.mathtext`](/slides/python-net/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)

