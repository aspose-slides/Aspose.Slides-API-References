---
title: IExcelDataWorkbook class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.excel/iexceldataworkbook/
---
## IExcelDataWorkbook 類別

表示一個工作簿，可供一般使用者存取 Excel 資料。

IExcelDataWorkbook 類型公開以下成員：

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/zh-hant/aspose.slides.excel/iexceldataworkbook/get_cell/#int-int-int) | 從指定的工作表中，使用其索引和儲存格座標擷取儲存格。 |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/zh-hant/aspose.slides.excel/iexceldataworkbook/get_cell/#str-int-int) | 從指定的工作表中，使用其名稱和儲存格座標擷取儲存格。 |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/zh-hant/aspose.slides.excel/iexceldataworkbook/get_cell/#int-str) | 從指定的工作表中，使用其索引和 Excel 風格的儲存格名稱 (例如 "B2") 擷取儲存格。 |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/zh-hant/aspose.slides.excel/iexceldataworkbook/get_cell/#str-str) | 從指定的工作表中，使用 Excel 風格的儲存格名稱 (例如 "B2") 擷取儲存格。 |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/zh-hant/aspose.slides.excel/iexceldataworkbook/get_cells/#str-bool) | 從工作簿中擷取符合指定公式的儲存格集合。 |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/zh-hant/aspose.slides.excel/iexceldataworkbook/get_charts_from_worksheet/#str) | 擷取包含 Excel 工作簿中指定工作表所有圖表索引與名稱的字典。 |
| [`get_worksheet_names(self)`](/slides/python-net/zh-hant/aspose.slides.excel/iexceldataworkbook/get_worksheet_names/#) | 擷取 Excel 工作簿中所有工作表的名稱。 |

### 另請參閱
* 模組 [`aspose.slides.excel`](/slides/python-net/zh-hant/aspose.slides.excel)
* 函式庫 [`Aspose.Slides`](/slides/python-net)