---
title: StringChartValue class
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides.charts/stringchartvalue/
---
## StringChartValue 类

表示可以以两种方式存储在 pptx 演示文稿中的字符串值：
1) 在与图表关联的工作簿的单元格/单元格中；
2) 作为文字值。

**继承：**[`StringChartValue`](/slides/python-net/zh/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/zh/aspose.slides.charts/basechartvalue)

StringChartValue 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`data_source_type`](/slides/python-net/zh/aspose.slides.charts/stringchartvalue/data_source_type/) | 指定后代中是否实际存在 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble <br/>属性。换句话说，它指定 Data 属性的值的类型。<br/>读写 [`DataSourceType`](/slides/python-net/zh/aspose.slides.charts/datasourcetype)。 |
| [`data`](/slides/python-net/zh/aspose.slides.charts/stringchartvalue/data/) | 返回或设置 Data 对象。<br/>读写 **any**。 |
| [`as_cells`](/slides/python-net/zh/aspose.slides.charts/stringchartvalue/as_cells/) | 不允许赋值为 Null。<br/>返回的值始终不是 None。<br/>读写 [`IChartCellCollection`](/slides/python-net/zh/aspose.slides.charts/ichartcellcollection)。 |
| [`as_literal_string`](/slides/python-net/zh/aspose.slides.charts/stringchartvalue/as_literal_string/) | 返回或设置为文字字符串的值。<br/>读写 **str**。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/zh/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | 从指定单元格设置值。 |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/zh/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | 如果 DataSourceType 属性是 DataSourceType.Worksheet，则此方法返回工作簿中表示字符串数据的单元格的地址<br/>否则返回空字符串。 |

### 另请参见
* 类 [`BaseChartValue`](/slides/python-net/zh/aspose.slides.charts/basechartvalue)
* 类 [`StringChartValue`](/slides/python-net/zh/aspose.slides.charts/stringchartvalue)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)