---
title: ChartPlotArea class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea 类

表示绘制图表的矩形区域。

ChartPlotArea 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`format`](/slides/python-net/zh/aspose.slides.charts/chartplotarea/format/) | 返回绘图区域的格式。<br/>            只读 [`IFormat`](/slides/python-net/zh/aspose.slides.charts/iformat)。 |
| [`x`](/slides/python-net/zh/aspose.slides.charts/chartplotarea/x/) | 以图表宽度的比例（0 到 1）返回或设置绘图区域边界框左上角的 x 坐标。<br/>            读写 **float**。 |
| [`y`](/slides/python-net/zh/aspose.slides.charts/chartplotarea/y/) | 以图表高度的比例（0 到 1）返回或设置绘图区域边界框左上角的 y 坐标。<br/>            读写 **float**。 |
| [`width`](/slides/python-net/zh/aspose.slides.charts/chartplotarea/width/) | 以图表宽度的比例（0 到 1）返回或设置绘图区域边界框的宽度。<br/>            读写 **float**。 |
| [`height`](/slides/python-net/zh/aspose.slides.charts/chartplotarea/height/) | 以图表高度的比例（0 到 1）返回或设置绘图区域边界框的高度。<br/>            读写 **float**。 |
| [`right`](/slides/python-net/zh/aspose.slides.charts/chartplotarea/right/) | 右侧。<br/>            只读 **float**。 |
| [`bottom`](/slides/python-net/zh/aspose.slides.charts/chartplotarea/bottom/) | 底部。<br/>            只读 **float**。 |
| [`chart`](/slides/python-net/zh/aspose.slides.charts/chartplotarea/chart/) | 图表。<br/>            只读 [`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart)。 |
| [`is_location_autocalculated`](/slides/python-net/zh/aspose.slides.charts/chartplotarea/is_location_autocalculated/) | 定义应如何计算位置：true – 自动计算；由 X、Y、Width、Height 属性定义。<br/>            只读 **bool**。 |
| [`layout_target_type`](/slides/python-net/zh/aspose.slides.charts/chartplotarea/layout_target_type/) | 如果绘图区域布局手动定义，此属性指定是按内部（不包括坐标轴和坐标轴标签）还是外部（包括坐标轴和坐标轴标签）布局绘图区域。<br/>            读写 [`ChartPlotArea.layout_target_type`](/slides/python-net/zh/aspose.slides.charts/chartplotarea/layout_target_type)。 |
| [`actual_x`](/slides/python-net/zh/aspose.slides.charts/chartplotarea/actual_x/) | 指定相对于图表左上角的实际 x 位置（左）。在获取实际值前请先调用 IChart.ValidateChartLayout() 方法。<br/>            只读 **float**。 |
| [`actual_y`](/slides/python-net/zh/aspose.slides.charts/chartplotarea/actual_y/) | 指定相对于图表左上角的实际顶部位置。 在获取实际值前请先调用 IChart.ValidateChartLayout() 方法。<br/>            只读 **float**。 |
| [`actual_width`](/slides/python-net/zh/aspose.slides.charts/chartplotarea/actual_width/) | 指定图表元素的实际宽度。 在获取实际值前请先调用 IChart.ValidateChartLayout() 方法。<br/>            只读 **float**。 |
| [`actual_height`](/slides/python-net/zh/aspose.slides.charts/chartplotarea/actual_height/) | 指定图表元素的实际高度。 在获取实际值前请先调用 IChart.ValidateChartLayout() 方法。<br/>            只读 **float**。 |
| [`slide`](/slides/python-net/zh/aspose.slides.charts/chartplotarea/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides.charts/chartplotarea/presentation/) |  |


### 另请参阅
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)