---
title: value_type property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/errorbarsformat/value_type/
weight: 120
---
## value_type 属性
表示确定误差线长度的可能方式。 
如果是自定义值类型，要指定值，请使用系列的 DataPoints 集合中特定数据点的 [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 属性。 
如果是 Fixed、Percentage 或 StandardDeviation 值类型，请使用 Value 属性来指定值。  
可读写 [`ErrorBarValueType`](/slides/python-net/zh/aspose.slides.charts/errorbarvaluetype)。

### 定义:
```python
@property
def value_type(self):
    ...

@value_type.setter
def value_type(self, value):
    ...
```

### 另见
* 类 [`ErrorBarsFormat`](/slides/python-net/zh/aspose.slides.charts/errorbarsformat)
* 枚举 [`ErrorBarValueType`](/slides/python-net/zh/aspose.slides.charts/errorbarvaluetype)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)