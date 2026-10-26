---
title: IExcelDataWorkbook class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.excel/iexceldataworkbook/
---
## IExcelDataWorkbook 类

表示提供对 Excel 数据进行通用访问的工作簿。

IExcelDataWorkbook 类型公开以下成员：

## 方法

| Method | Description |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/zh/aspose.slides.excel/iexceldataworkbook/get_cell/#int-int-int) | 使用其索引和单元格坐标从指定的工作表检索单元格。 |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/zh/aspose.slides.excel/iexceldataworkbook/get_cell/#str-int-int) | 使用其名称和单元格坐标从指定的工作表检索单元格。 |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/zh/aspose.slides.excel/iexceldataworkbook/get_cell/#int-str) | 使用其索引和 Excel 样式的单元格名称（例如 "B2"）从指定的工作表检索单元格。 |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/zh/aspose.slides.excel/iexceldataworkbook/get_cell/#str-str) | 使用 Excel 样式的单元格名称（例如 "B2"）从指定的工作表检索单元格。 |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/zh/aspose.slides.excel/iexceldataworkbook/get_cells/#str-bool) | 检索工作簿中符合指定公式的单元格集合。 |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/zh/aspose.slides.excel/iexceldataworkbook/get_charts_from_worksheet/#str) | 检索包含 Excel 工作簿中指定工作表的所有图表的索引和名称的字典。 |
| [`get_worksheet_names(self)`](/slides/python-net/zh/aspose.slides.excel/iexceldataworkbook/get_worksheet_names/#) | 检索 Excel 工作簿中包含的所有工作表的名称。 |

### 另见
* 模块 [`aspose.slides.excel`](/slides/python-net/zh/aspose.slides.excel)
* 库 [`Aspose.Slides`](/slides/python-net)