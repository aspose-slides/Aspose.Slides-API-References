---
title: ChartDataCell class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/chartdatacell/
---
## ChartDataCell 类

表示图表数据的单元格。

ChartDataCell 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`row`](/slides/python-net/zh/aspose.slides.charts/chartdatacell/row/) | 返回单元格所在工作表的行索引。<br/>            只读 **int**。 |
| [`column`](/slides/python-net/zh/aspose.slides.charts/chartdatacell/column/) | 返回单元格所在工作表的列索引。<br/>            只读 **int**。 |
| [`value`](/slides/python-net/zh/aspose.slides.charts/chartdatacell/value/) | 获取或设置单元格的值。<br/>            读写 **any**。 |
| [`formula`](/slides/python-net/zh/aspose.slides.charts/chartdatacell/formula/) | 获取或设置 A1 样式的公式。 |
| [`r1c1_formula`](/slides/python-net/zh/aspose.slides.charts/chartdatacell/r1c1_formula/) | 获取或设置 R1C1 样式的公式。 |
| [`chart_data_worksheet`](/slides/python-net/zh/aspose.slides.charts/chartdatacell/chart_data_worksheet/) | 获取工作表。<br/>            只读 [`IChartDataWorksheet`](/slides/python-net/zh/aspose.slides.charts/ichartdataworksheet)。 |
| [`is_hidden`](/slides/python-net/zh/aspose.slides.charts/chartdatacell/is_hidden/) | 确定单元格是否隐藏。<br/>            只读 **bool**。 |
| [`custom_number_format`](/slides/python-net/zh/aspose.slides.charts/chartdatacell/custom_number_format/) | 获取或设置数字和日期的自定义显示格式。<br/>            如果值为空，将使用 PresetNumberFormat 的值。<br/>            读写 **str**。 |
| [`preset_number_format`](/slides/python-net/zh/aspose.slides.charts/chartdatacell/preset_number_format/) | 获取或设置数字和日期的内建显示格式。Preset number 必须在 [0..22] 或 [37..49] 范围内。<br/>            读写 **int**。 |

## 方法

| Method | Description |
| :- | :- |
| [`calculate(self, update_values)`](/slides/python-net/zh/aspose.slides.charts/chartdatacell/calculate/#bool) | 如果单元格包含公式，将根据该公式更新其值。 |


### 参见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)