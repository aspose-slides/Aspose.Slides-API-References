---
title: set_range method
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides.charts/chartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Set chart data range. Series and categories will be updated based on new data range.
            If amount of series in data range greater than count of series in the chart data then additional series with the same type
            as a last series in the current collection will be added to the end of the collection.

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
| **RuntimeError(Proxy error(ArgumentException))** | formula 格式不正确。 |

### 另见
* 类 [`ChartData`](/slides/python-net/zh/aspose.slides.charts/chartdata)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)