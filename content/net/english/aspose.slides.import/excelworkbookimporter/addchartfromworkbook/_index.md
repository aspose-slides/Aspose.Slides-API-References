---
title: AddChartFromWorkbook
second_title: Aspose.Sildes for .NET API Reference
description: Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates.
type: docs
weight: 10
url: /aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, int, bool) {#addchartfromworkbook}

Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, int chartIndex, bool embedAllWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | The shape collection to which the chart will be added. |
| x | Single | The X coordinate for positioning the chart. |
| y | Single | The Y coordinate for positioning the chart. |
| workbook | IExcelDataWorkbook | The Excel workbook. |
| worksheetName | String | The name of the worksheet that contains the chart. |
| chartIndex | Int32 | The zero-based index of the chart shape to insert. This index can be obtained using the [`GetChartsFromWorksheet`](../../../aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet) method. |
| embedAllWorkbook | Boolean | If `true`, the entire workbook will be embedded in the chart; if `false`, only the chart data will be embedded. |

### Return Value

The chart that was added to the shape collection.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when any required parameter is null, empty, or if the chart cannot be found in the workbook. |

### Examples

Example:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, wb, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* interface [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string, bool) {#addchartfromworkbook_1}

Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | The shape collection to which the chart will be added. |
| x | Single | The X coordinate for positioning the chart. |
| y | Single | The Y coordinate for positioning the chart. |
| workbook | IExcelDataWorkbook | The Excel workbook. |
| worksheetName | String | The name of the worksheet that contains the chart. |
| chartName | String | The name of the chart to be added. |
| embedAllWorkbook | Boolean | If `true`, the entire workbook will be embedded in the chart; if `false`, only the chart data will be embedded. |

### Return Value

The chart that was added to the shape collection.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when any required parameter is null, empty, or if the chart cannot be found in the workbook. |

### Examples

Example:

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

### See Also

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* interface [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, Stream, string, string, bool) {#addchartfromworkbook_2}

Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | The shape collection to which the chart will be added. |
| x | Single | The X coordinate for positioning the chart. |
| y | Single | The Y coordinate for positioning the chart. |
| workbookStream | Stream | A stream containing the workbook data. |
| worksheetName | String | The name of the worksheet that contains the chart. |
| chartName | String | The name of the chart to be added. |
| embedAllWorkbook | Boolean | If `true`, the entire workbook will be embedded in the chart; if `false`, only the chart data will be embedded. |

### Return Value

The chart that was added to the shape collection.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when any required parameter is null, empty, or if the chart cannot be found in the workbook. |
| InvalidOperationException | Thrown when the input data is in an unsupported format. |

### Examples

Example:

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.LayoutSlides[0].Shapes, 10, 10, fStream, worksheetName, chartName, true);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, string, string, string, bool) {#addchartfromworkbook_3}

Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string chartName, bool embedWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | The shape collection to which the chart will be added. |
| x | Single | The X coordinate for positioning the chart. |
| y | Single | The Y coordinate for positioning the chart. |
| workbookPath | String | The file path to the workbook containing the chart. |
| worksheetName | String | The name of the worksheet that contains the chart. |
| chartName | String | The name of the chart to be added. |
| embedWorkbook | Boolean | If `true`, the workbook will be embedded in the chart; if `false`, the chart will link to the external workbook. |

### Return Value

The chart that was added to the shape collection.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when any required parameter is null, empty, or if the chart cannot be found in the workbook. |
| IOException | Thrown when an I/O error occurs while accessing the file. |
| InvalidOperationException | Thrown when the input data is in an unsupported format. |

### Examples

Example:

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
