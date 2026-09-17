---
title: error_bars_x_format property
second_title: Aspose.Slides 用于 Python 的 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartseries/error_bars_x_format/
weight: 110
---
## error_bars_x_format 属性
表示具有 X 方向的系列的 ErrorBars。

            ErrorBars 具有 X 方向可用于类型为 area、bar、scatter 和 bubble 的系列。
            对于其他任何类型的图表，此属性返回 None（包括 3D 图表）。
            如果使用自定义值，请使用 DataPoints 集合来指定值（使用 [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 属性）。
            
            只读 [`IErrorBarsFormat`](/slides/python-net/zh/aspose.slides.charts/ierrorbarsformat)。

### 定义:
```python
@property
def error_bars_x_format(self):
    ...
```


### 另见
* 类 [`IChartSeries`](/slides/python-net/zh/aspose.slides.charts/ichartseries)
* 类 [`IErrorBarsFormat`](/slides/python-net/zh/aspose.slides.charts/ierrorbarsformat)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)