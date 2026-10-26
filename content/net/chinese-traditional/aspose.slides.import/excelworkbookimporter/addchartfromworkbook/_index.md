---
title: AddChartFromWorkbook
second_title: Aspose.Sildes for .NET API 參考文件
description: 從指定的 Excel 工作簿中檢索圖表，並將其新增至給定形狀集合的末端，位於指定的座標處。
type: docs
weight: 10
url: /zh-hant/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, int, bool) {#addchartfromworkbook}

從指定的 Excel 工作簿中檢索圖表，並將其新增到給定形狀集合的末端，位於指定的座標處。

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, int chartIndex, bool embedAllWorkbook)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapes | IShapeCollection | 將要新增圖表的形狀集合。 |
| x | Single | 圖表定位的 X 座標。 |
| y | Single | 圖表定位的 Y 座標。 |
| workbook | IExcelDataWorkbook | Excel 工作簿。 |
| worksheetName | String | 包含圖表的工作表名稱。 |
| chartIndex | Int32 | 要插入的圖表形狀的零基索引。此索引可使用 [`GetChartsFromWorksheet`](../../../aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet) 方法取得。 |
| embedAllWorkbook | Boolean | 若為 `true`，整個工作簿將嵌入圖表；若為 `false`，僅嵌入圖表資料。 |

### 返回值

已新增至形狀集合的圖表。

### 例外

| 例外 | 條件 |
| --- | --- |
| ArgumentException | 當任何必填參數為 null、空或找不到圖表於工作簿中時拋出。 |

### 範例

範例：

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, wb, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### 另請參閱

* 介面 [IChart](../../../aspose.slides.charts/ichart)
* 介面 [IShapeCollection](../../../aspose.slides/ishapecollection)
* 介面 [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* 類別 [ExcelWorkbookImporter](../../excelworkbookimporter)
* 命名空間 [Aspose.Slides.Import](../../excelworkbookimporter)
* 組件 [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string, bool) {#addchartfromworkbook_1}

從指定的 Excel 工作簿中檢索圖表，並將其新增到給定形狀集合的末端，位於指定的座標處。

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string chartName, bool embedAllWorkbook)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapes | IShapeCollection | 將要新增圖表的形狀集合。 |
| x | Single | 圖表定位的 X 座標。 |
| y | Single | 圖表定位的 Y 座標。 |
| workbook | IExcelDataWorkbook | Excel 工作簿。 |
| worksheetName | String | 包含圖表的工作表名稱。 |
| chartName | String | 要新增的圖表名稱。 |
| embedAllWorkbook | Boolean | 若為 `true`，整個工作簿將嵌入圖表；若為 `false`，僅嵌入圖表資料。 |

### 返回值

已新增至形狀集合的圖表。

### 例外

| 例外 | 條件 |
| --- | --- |
| ArgumentException | 當任何必填參數為 null、空或找不到圖表於工作簿中時拋出。 |

### 範例

範例：

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    string worksheetName = "worksheet name";
    var worksheetCharts = wb.GetChartsFromWorksheet(worksheetName);
    foreach (var chart in worksheetCharts)
    {
        ISlide slide = pres.Slides.AddEmptySlide(pres.LayoutSlides[0]);
        ExcelWorkbookImporter.AddChartFromWorkbook(slide.Shapes, 10, 10, wb, worksheetName, chart.Key, false);
    }
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### 另請參閱

* 介面 [IChart](../../../aspose.slides.charts/ichart)
* 介面 [IShapeCollection](../../../aspose.slides/ishapecollection)
* 介面 [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* 類別 [ExcelWorkbookImporter](../../excelworkbookimporter)
* 命名空間 [Aspose.Slides.Import](../../excelworkbookimporter)
* 組件 [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, Stream, string, string, bool) {#addchartfromworkbook_2}

從指定的 Excel 工作簿中檢索圖表，並將其新增到給定形狀集合的末端，位於指定的座標處。

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string chartName, bool embedAllWorkbook)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapes | IShapeCollection | 將要新增圖表的形狀集合。 |
| x | Single | 圖表定位的 X 座標。 |
| y | Single | 圖表定位的 Y 座標。 |
| workbookStream | Stream | 包含工作簿資料的串流。 |
| worksheetName | String | 包含圖表的工作表名稱。 |
| chartName | String | 要新增的圖表名稱。 |
| embedAllWorkbook | Boolean | 若為 `true`，整個工作簿將嵌入圖表；若為 `false`，僅嵌入圖表資料。 |

### 返回值

已新增至形狀集合的圖表。

### 例外

| 例外 | 條件 |
| --- | --- |
| ArgumentException | 當任何必填參數為 null、空或找不到圖表於工作簿中時拋出。 |
| InvalidOperationException | 當輸入資料為不支援的格式時拋出。 |

### 範例

範例：

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.LayoutSlides[0].Shapes, 10, 10, fStream, worksheetName, chartName, true);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### 另請參閱

* 介面 [IChart](../../../aspose.slides.charts/ichart)
* 介面 [IShapeCollection](../../../aspose.slides/ishapecollection)
* 類別 [ExcelWorkbookImporter](../../excelworkbookimporter)
* 命名空間 [Aspose.Slides.Import](../../excelworkbookimporter)
* 組件 [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, string, string, string, bool) {#addchartfromworkbook_3}

從指定的 Excel 工作簿中檢索圖表，並將其新增到給定形狀集合的末端，位於指定的座標處。

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string chartName, bool embedWorkbook)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapes | IShapeCollection | 將要新增圖表的形狀集合。 |
| x | Single | 圖表定位的 X 座標。 |
| y | Single | 圖表定位的 Y 座標。 |
| workbookPath | String | 包含圖表之工作簿的檔案路徑。 |
| worksheetName | String | 包含圖表的工作表名稱。 |
| chartName | String | 要新增的圖表名稱。 |
| embedWorkbook | Boolean | 若為 `true`，工作簿將嵌入圖表；若為 `false`，圖表將連結至外部工作簿。 |

### 返回值

已新增至形狀集合的圖表。

### 例外

| 例外 | 條件 |
| --- | --- |
| ArgumentException | 當任何必填參數為 null、空或找不到圖表於工作簿中時拋出。 |
| IOException | 當存取檔案時發生 I/O 錯誤時拋出。 |
| InvalidOperationException | 當輸入資料為不支援的格式時拋出。 |

### 範例

範例：

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### 另請參閱

* 介面 [IChart](../../../aspose.slides.charts/ichart)
* 介面 [IShapeCollection](../../../aspose.slides/ishapecollection)
* 類別 [ExcelWorkbookImporter](../../excelworkbookimporter)
* 命名空間 [Aspose.Slides.Import](../../excelworkbookimporter)
* 組件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->