---
title: IStringChartValue class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/istringchartvalue/
---
## IStringChartValue 类

表示可以以两种方式存储在 pptx 演示文稿中的字符串值：
1) 在与图表关联的工作簿的单元格中；
2) 作为文字值。

IStringChartValue 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`as_literal_string`](/slides/python-net/zh/aspose.slides.charts/istringchartvalue/as_literal_string/) | 如果 DataSourceType 属性是 DataSourceType.StringLiterals，则返回或设置文字字符串。<br/>读取/写入 **str**. |
| [`as_cells`](/slides/python-net/zh/aspose.slides.charts/istringchartvalue/as_cells/) |  |
| [`data_source_type`](/slides/python-net/zh/aspose.slides.charts/istringchartvalue/data_source_type/) |  |
| [`data`](/slides/python-net/zh/aspose.slides.charts/istringchartvalue/data/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`to_string(self)`](/slides/python-net/zh/aspose.slides.charts/istringchartvalue/to_string/#) | 返回字符串表示。 |
| [`set_from_one_cell(self, cell)`](/slides/python-net/zh/aspose.slides.charts/istringchartvalue/set_from_one_cell/#ichartdatacell) | 从指定单元格设置值。 |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/zh/aspose.slides.charts/istringchartvalue/get_cells_address_in_workbook/#) | 如果 DataSourceType 属性是 DataSourceType.Worksheet，则此方法返回工作簿中表示字符串数据的单元格地址<br/>否则返回空字符串。 |

### 参见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)