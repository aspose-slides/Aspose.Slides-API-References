---
title: add_table_from_workbook method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
從指定的 Excel 活頁簿中擷取表格，並在指定座標將其加入至給定形狀集合的末端。

### 返回值

已加入形狀集合的表格。



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection) | 將要加入表格的形狀集合。 |
| x | **float** | 用於定位表格的 X 座標。 |
| y | **float** | 用於定位表格的 Y 座標。 |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/zh-hant/aspose.slides.excel/iexceldataworkbook) | Excel 活頁簿。 |
| worksheet_name | **str** | 包含表格的工作表名稱。 |
| cell_range | **str** | 定義表格的儲存格範圍（例如 "A1:D10"）。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 當任何必需的參數為 None 或為空，或指定的工作表或儲存格範圍無效時拋出此例外。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當輸入資料的格式不受支援時拋出此例外。 |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
從指定的 Excel 活頁簿檔案中擷取表格，並在指定座標將其加入至給定形狀集合的末端。

### 返回值

已加入形狀集合的表格。



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection) | 將要加入表格的形狀集合。 |
| x | **float** | 用於定位表格的 X 座標。 |
| y | **float** | 用於定位表格的 Y 座標。 |
| workbook_path | **str** | Excel 活頁簿檔案的路徑。 |
| worksheet_name | **str** | 包含表格的工作表名稱。 |
| cell_range | **str** | 定義表格的儲存格範圍（例如 "A1:D10"）。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 當任何必需的參數為 None 或為空，或指定的工作表或儲存格範圍無效時拋出此例外。 |
| **RuntimeError(Proxy error(IOException))** | 在存取活頁簿檔案時發生 I/O 錯誤時拋出此例外。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當輸入資料的格式不受支援時拋出此例外。 |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
從指定的 Excel 活頁簿檔案中擷取表格，並在指定座標將其加入至給定形狀集合的末端。

### 返回值

已加入形狀集合的表格。



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection) | 將要加入表格的形狀集合。 |
| x | **float** | 用於定位表格的 X 座標。 |
| y | **float** | 用於定位表格的 Y 座標。 |
| workbook_stream | **io.RawIOBase** | 包含活頁簿資料的串流。 |
| worksheet_name | **str** | 包含表格的工作表名稱。 |
| cell_range | **str** | 定義表格的儲存格範圍（例如 "A1:D10"）。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 當任何必需的參數為 None 或為空，或指定的工作表或儲存格範圍無效時拋出此例外。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當輸入資料的格式不受支援時拋出此例外。 |



### 另請參閱
* 類別 [`ExcelWorkbookImporter`](/slides/python-net/zh-hant/aspose.slides.importing/excelworkbookimporter)
* 類別 [`IExcelDataWorkbook`](/slides/python-net/zh-hant/aspose.slides.excel/iexceldataworkbook)
* 類別 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* 類別 [`ITable`](/slides/python-net/zh-hant/aspose.slides/itable)
* 模組 [`aspose.slides.importing`](/slides/python-net/zh-hant/aspose.slides.importing)
* 程式庫 [`Aspose.Slides`](/slides/python-net)