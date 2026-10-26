---
title: add_chart_from_workbook method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
從指定的 Excel 活頁簿中取得圖表，並將其新增至給定形狀集合的末端，位於指定的座標。

### 返回值

已新增至形狀集合的圖表。

```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection) | 將要加入圖表的形狀集合。 |
| x | **float** | 用於定位圖表的 X 座標。 |
| y | **float** | 用於定位圖表的 Y 座標。 |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/zh-hant/aspose.slides.excel/iexceldataworkbook) | Excel 活頁簿。 |
| worksheet_name | **str** | 包含圖表之工作表的名稱。 |
| chart_index | **int** | 要插入的圖表形狀的零基索引。 <br/><br/>            此索引可使用 **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste** 方法取得。 |
| embed_all_workbook | **bool** | 若為 `true`，整個活頁簿將嵌入於圖表中； <br/><br/>            若為 `false`，則僅嵌入圖表資料。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 當任何必要參數為 None、空值，或在活頁簿中找不到圖表時拋出此例外。 |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
從指定的 Excel 活頁簿中取得圖表，並將其新增至給定形狀集合的末端，位於指定的座標。

### 返回值

已新增至形狀集合的圖表。

```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection) | 將要加入圖表的形狀集合。 |
| x | **float** | 用於定位圖表的 X 座標。 |
| y | **float** | 用於定位圖表的 Y 座標。 |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/zh-hant/aspose.slides.excel/iexceldataworkbook) | Excel 活頁簿。 |
| worksheet_name | **str** | 包含圖表之工作表的名稱。 |
| chart_name | **str** | 要加入之圖表的名稱。 |
| embed_all_workbook | **bool** | 若為 `true`，整個活頁簿將嵌入於圖表中； <br/><br/>            若為 `false`，則僅嵌入圖表資料。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 當任何必要參數為 None、空值，或在活頁簿中找不到圖表時拋出此例外。 |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
從指定的 Excel 活頁簿中取得圖表，並將其新增至給定形狀集合的末端，位於指定的座標。

### 返回值

已新增至形狀集合的圖表。

```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection) | 將要加入圖表的形狀集合。 |
| x | **float** | 用於定位圖表的 X 座標。 |
| y | **float** | 用於定位圖表的 Y 座標。 |
| workbook_stream | **io.RawIOBase** | 包含活頁簿資料的串流。 |
| worksheet_name | **str** | 包含圖表之工作表的名稱。 |
| chart_name | **str** | 要加入之圖表的名稱。 |
| embed_all_workbook | **bool** | 若為 `true`，整個活頁簿將嵌入於圖表中； <br/><br/>            若為 `false`，則僅嵌入圖表資料。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 當任何必要參數為 None、空值，或在活頁簿中找不到圖表時拋出此例外。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當輸入資料為不支援的格式時拋出此例外。 |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
從指定的 Excel 活頁簿中取得圖表，並將其新增至給定形狀集合的末端，位於指定的座標。

### 返回值

已新增至形狀集合的圖表。

```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection) | 將要加入圖表的形狀集合。 |
| x | **float** | 用於定位圖表的 X 座標。 |
| y | **float** | 用於定位圖表的 Y 座標。 |
| workbook_path | **str** | 包含圖表之活頁簿的檔案路徑。 |
| worksheet_name | **str** | 包含圖表之工作表的名稱。 |
| chart_name | **str** | 要加入之圖表的名稱。 |
| embed_workbook | **bool** | 若為 `true`，活頁簿將嵌入於圖表中； <br/><br/>            若為 `false`，圖表將連結至外部活頁簿。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 當任何必要參數為 None、空值，或在活頁簿中找不到圖表時拋出此例外。 |
| **RuntimeError(Proxy error(IOException))** | 在存取檔案時發生 I/O 錯誤時拋出此例外。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當輸入資料為不支援的格式時拋出此例外。 |



### 另見
* 類別 [`ExcelWorkbookImporter`](/slides/python-net/zh-hant/aspose.slides.importing/excelworkbookimporter)
* 類別 [`IExcelDataWorkbook`](/slides/python-net/zh-hant/aspose.slides.excel/iexceldataworkbook)
* 類別 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* 模組 [`aspose.slides.importing`](/slides/python-net/zh-hant/aspose.slides.importing)
* 函式庫 [`Aspose.Slides`](/slides/python-net)