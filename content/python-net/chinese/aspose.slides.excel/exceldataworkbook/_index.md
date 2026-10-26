---
title: ExcelDataWorkbook class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.excel/exceldataworkbook/
---
## ExcelDataWorkbook 类

表示一个工作簿，提供对 Excel 数据的一般访问。

ExcelDataWorkbook 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self, file_path)`](/slides/python-net/zh/aspose.slides.excel/exceldataworkbook/__init__/#str) | 使用指定的文件路径初始化新实例。 |
| [`__init__(self, stream)`](/slides/python-net/zh/aspose.slides.excel/exceldataworkbook/__init__/#iorawiobase) | 使用提供的流初始化类的新实例。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/zh/aspose.slides.excel/exceldataworkbook/get_cell/#int-int-int) | 使用索引和单元格坐标从指定的工作表检索单元格。 |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/zh/aspose.slides.excel/exceldataworkbook/get_cell/#str-int-int) | 使用名称和单元格坐标从指定的工作表检索单元格。 |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/zh/aspose.slides.excel/exceldataworkbook/get_cell/#int-str) | 使用索引和 Excel 样式的单元格名称（例如 "B2"）从指定的工作表检索单元格。 |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/zh/aspose.slides.excel/exceldataworkbook/get_cell/#str-str) | 使用 Excel 样式的单元格名称（例如 "B2"）从指定的工作表检索单元格。 |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/zh/aspose.slides.excel/exceldataworkbook/get_cells/#str-bool) | 检索工作簿中匹配指定公式的单元格集合。 |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/zh/aspose.slides.excel/exceldataworkbook/get_charts_from_worksheet/#str) | 检索包含 Excel 工作簿指定工作表中所有图表的索引和名称的字典。 |
| [`get_worksheet_names(self)`](/slides/python-net/zh/aspose.slides.excel/exceldataworkbook/get_worksheet_names/#) | 检索 Excel 工作簿中包含的所有工作表的名称。 |

### 另请参见
* 模块 [`aspose.slides.excel`](/slides/python-net/zh/aspose.slides.excel)
* 库 [`Aspose.Slides`](/slides/python-net)