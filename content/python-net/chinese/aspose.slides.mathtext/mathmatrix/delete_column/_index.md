---
title: delete_column method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
删除指定的列


```python
def delete_column(self, column_index):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| column_index | **int** | 要删除的列的零基索引。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 当您尝试删除矩阵中唯一的最后一列时 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 如果 columnIndex 小于零或大于或等于 ColumnCount |



### 另请参见
* 类 [`MathMatrix`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)