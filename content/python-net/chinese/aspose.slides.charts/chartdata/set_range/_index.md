---
title: set_range method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
设置图表数据范围。Series 和 categories 将基于新的数据范围进行更新。
如果数据范围中的 series 数量大于图表数据中的 series 计数，则会在当前集合的末尾添加与当前集合中最后一个 series 具有相同类型的额外 series。

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
| **RuntimeError(Proxy error(InvalidOperationException))** | 不支持的图表类型 |
| **RuntimeError(Proxy error(ArgumentException))** | formula 的格式不正确。 |

### 另见
* 类 [`ChartData`](/slides/python-net/zh/aspose.slides.charts/chartdata)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)