---
title: ExcelDataWorkbook class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.excel/exceldataworkbook/
---
## ExcelDataWorkbook 類別

Represents a workbook that provides access to Excel data for general use.

The ExcelDataWorkbook type exposes the following members:

## 建構子

| 建構子 | 說明 |
| :- | :- |
| [`__init__(self, file_path)`](/slides/python-net/zh-hant/aspose.slides.excel/exceldataworkbook/__init__/#str) | 使用指定的檔案路徑初始化新實例。 |
| [`__init__(self, stream)`](/slides/python-net/zh-hant/aspose.slides.excel/exceldataworkbook/__init__/#iorawiobase) | 使用提供的串流初始化類別的新實例。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/zh-hant/aspose.slides.excel/exceldataworkbook/get_cell/#int-int-int) | 根據索引和儲存格座標，從指定的工作表取得儲存格。 |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/zh-hant/aspose.slides.excel/exceldataworkbook/get_cell/#str-int-int) | 根據名稱和儲存格座標，從指定的工作表取得儲存格。 |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/zh-hant/aspose.slides.excel/exceldataworkbook/get_cell/#int-str) | 根據索引與 Excel 風格的儲存格名稱（例如 "B2"），從指定的工作表取得儲存格。 |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/zh-hant/aspose.slides.excel/exceldataworkbook/get_cell/#str-str) | 根據 Excel 風格的儲存格名稱（例如 "B2"），從指定的工作表取得儲存格。 |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/zh-hant/aspose.slides.excel/exceldataworkbook/get_cells/#str-bool) | 從工作簿中取得符合指定公式的儲存格集合。 |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/zh-hant/aspose.slides.excel/exceldataworkbook/get_charts_from_worksheet/#str) | 取得一個字典，內容包含 Excel 工作簿中指定工作表的所有圖表的索引與名稱。 |
| [`get_worksheet_names(self)`](/slides/python-net/zh-hant/aspose.slides.excel/exceldataworkbook/get_worksheet_names/#) | 取得 Excel 工作簿中所有工作表的名稱。 |


### 另請參閱
* 模組 [`aspose.slides.excel`](/slides/python-net/zh-hant/aspose.slides.excel)
* 函式庫 [`Aspose.Slides`](/slides/python-net)