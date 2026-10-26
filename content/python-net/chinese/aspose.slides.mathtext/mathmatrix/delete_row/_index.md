---
title: delete_row method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
删除指定的行


```python
def delete_row(self, row_index):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| row_index | **int** | 要删除的行的零基索引。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 当您尝试删除矩阵中唯一的最后一行时 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 如果 rowIndex 小于零或大于等于 RowCount |



### 另见
* 类 [`MathMatrix`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)