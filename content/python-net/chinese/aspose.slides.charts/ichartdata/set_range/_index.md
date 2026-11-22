---
title: set_range method
second_title: Aspose.Slides 用于 Python 的 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
设置图表数据范围。系列和类别将根据新数据范围进行更新。
如果数据范围中的系列数量大于图表数据中的系列计数，则会在当前集合的末尾添加与当前集合最后一个系列类型相同的附加系列。

```python
def set_range(self, formula):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| formula | **str** | 单元格数据范围公式。例如："Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula 为 None。 |
| **RuntimeError(Proxy error(ArgumentException))** | formula 格式不正确。 |

### 参见
* 类 [`IChartData`](/slides/python-net/zh/aspose.slides.charts/ichartdata)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)