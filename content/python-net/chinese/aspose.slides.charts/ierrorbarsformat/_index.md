---
title: IErrorBarsFormat class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ierrorbarsformat/
---
## IErrorBarsFormat 类

表示图表系列的误差线。ErrorBars 的自定义值位于 IChartDataPointCollection（在 [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 属性中）。

IErrorBarsFormat 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/zh/aspose.slides.charts/ierrorbarsformat/type/) | 获取或设置误差线的类型。<br/>            读/写 [`ErrorBarType`](/slides/python-net/zh/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/zh/aspose.slides.charts/ierrorbarsformat/value_type/) | 表示确定误差线长度的可能方式。<br/>            在自定义值类型的情况下，要指定值请使用系列的 DataPoints 集合中特定数据点的 [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/zh/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 属性。  <br/>            读/写 [`ErrorBarValueType`](/slides/python-net/zh/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/zh/aspose.slides.charts/ierrorbarsformat/has_end_cap/) | 指定在误差线的末端不绘制端帽。<br/>            读/写 **bool**. |
| [`value`](/slides/python-net/zh/aspose.slides.charts/ierrorbarsformat/value/) | 获取或设置在 Fixed、Percentage 和 StandardDeviation 值类型下用于确定误差线长度的值。<br/>            读/写 **float**. |
| [`format`](/slides/python-net/zh/aspose.slides.charts/ierrorbarsformat/format/) | 表示误差线的格式。<br/>            读/写 [`IFormat`](/slides/python-net/zh/aspose.slides.charts/iformat). |
| [`is_visible`](/slides/python-net/zh/aspose.slides.charts/ierrorbarsformat/is_visible/) | 获取或设置误差线的可见性。<br/>            读/写 **bool**. |
| [`chart`](/slides/python-net/zh/aspose.slides.charts/ierrorbarsformat/chart/) |  |
| [`slide`](/slides/python-net/zh/aspose.slides.charts/ierrorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides.charts/ierrorbarsformat/presentation/) |  |

### 另见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)