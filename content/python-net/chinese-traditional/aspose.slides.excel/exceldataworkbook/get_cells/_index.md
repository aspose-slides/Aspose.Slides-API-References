---
title: get_cells method
second_title: Aspose.Slides 用於 Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.excel/exceldataworkbook/get_cells/
weight: 30
---
## get_cells(self, formula, skip_hidden_cells) {#str-bool}
檢索工作簿中符合指定公式的儲存格集合。

### 回傳

一個唯讀的儲存格清單，符合指定的公式。

```python
def get_cells(self, formula, skip_hidden_cells):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| formula | **str** | 用於識別目標儲存格的公式或範圍表達式（例如 "Sheet1!A1:B3"）。 |
| skip_hidden_cells | **bool** | 如果 `true`，隱藏的儲存格（例如隱藏的列或欄）將不會包含在結果中。 |

### 另見
* 類別 [`ExcelDataWorkbook`](/slides/python-net/zh-hant/aspose.slides.excel/exceldataworkbook)
* 模組 [`aspose.slides.excel`](/slides/python-net/zh-hant/aspose.slides.excel)
* 函式庫 [`Aspose.Slides`](/slides/python-net)