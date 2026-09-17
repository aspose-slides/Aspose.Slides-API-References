---
title: StringOrDoubleChartValue class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/stringordoublechartvalue/
---
## StringOrDoubleChartValue 类

表示可以以两种方式存储在 pptx 演示文稿中的字符串或双精度值：
            1) 在与图表关联的工作簿的单元格/单元格中；
            2) 作为文字值。

**继承:**[`StringOrDoubleChartValue`](/slides/python-net/zh/aspose.slides.charts/stringordoublechartvalue) → [`BaseChartValue`](/slides/python-net/zh/aspose.slides.charts/basechartvalue)

StringOrDoubleChartValue 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`data_source_type`](/slides/python-net/zh/aspose.slides.charts/stringordoublechartvalue/data_source_type/) | 指定在派生类中是否实际存在 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble <br/>            属性。换句话说，它指定 Data 属性的值的类型 <br/>            。读取/写入 [`DataSourceType`](/slides/python-net/zh/aspose.slides.charts/datasourcetype)。 |
| [`data`](/slides/python-net/zh/aspose.slides.charts/stringordoublechartvalue/data/) | 返回或设置 Data 对象。<br/>            读取/写入 **any**。 |
| [`as_cell`](/slides/python-net/zh/aspose.slides.charts/stringordoublechartvalue/as_cell/) | 返回或设置图表数据单元格。<br/>            读取/写入 [`IChartDataCell`](/slides/python-net/zh/aspose.slides.charts/ichartdatacell)。 |
| [`as_literal_string`](/slides/python-net/zh/aspose.slides.charts/stringordoublechartvalue/as_literal_string/) | 返回或设置值为文字字符串。<br/>            读取/写入 **str**。 |
| [`as_literal_double`](/slides/python-net/zh/aspose.slides.charts/stringordoublechartvalue/as_literal_double/) | 返回或设置值为文字双精度。<br/>            读取/写入 **float**。 |

## 方法

| Method | Description |
| :- | :- |
| [`to_double(self)`](/slides/python-net/zh/aspose.slides.charts/stringordoublechartvalue/to_double/#) | 转换为双精度。 |

### 另见
* 类 [`BaseChartValue`](/slides/python-net/zh/aspose.slides.charts/basechartvalue)
* 类 [`StringOrDoubleChartValue`](/slides/python-net/zh/aspose.slides.charts/stringordoublechartvalue)
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)