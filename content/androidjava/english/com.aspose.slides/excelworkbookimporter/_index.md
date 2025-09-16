---
title: ExcelWorkbookImporter
second_title: Aspose.Slides for Android via Java API Reference
description: Provides functionality for importing content from an Excel workbook into a presentation.
type: docs
url: /com.aspose.slides/excelworkbookimporter/
---
**Inheritance:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

Provides functionality for importing content from an Excel workbook into a presentation.
## Methods

| Method | Description |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates. |
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```


Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, wb, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | The shape collection to which the chart will be added. |
| x | float | The X coordinate for positioning the chart. |
| y | float | The Y coordinate for positioning the chart. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | The Excel workbook. |
| worksheetName | java.lang.String | The name of the worksheet that contains the chart. |
| chartIndex | int | The zero-based index of the chart shape to insert. This index can be obtained using the [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-) method. |
| embedAllWorkbook | boolean | If true, the entire workbook will be embedded in the chart; if false, only the chart data will be embedded. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - The chart that was added to the shape collection.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```


Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      String worksheetName = "worksheet name";
>      Dictionary.Enumerator<Integer, String> worksheetCharts = wb.getChartsFromWorksheet(worksheetName).iterator();
>      while (worksheetCharts.hasNext())
>      {
>          KeyValuePair<Integer, String> chart = worksheetCharts.next();
>          ISlide slide = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>          ExcelWorkbookImporter.addChartFromWorkbook(slide.getShapes(), 10, 10, wb, worksheetName, chart.getKey(), false);
>      }
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | The shape collection to which the chart will be added. |
| x | float | The X coordinate for positioning the chart. |
| y | float | The Y coordinate for positioning the chart. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | The Excel workbook. |
| worksheetName | java.lang.String | The name of the worksheet that contains the chart. |
| chartName | java.lang.String | The name of the chart to be added. |
| embedAllWorkbook | boolean | If true, the entire workbook will be embedded in the chart; if false, only the chart data will be embedded. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - The chart that was added to the shape collection.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```


Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fStream = new FileInputStream(workbookPath);
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getLayoutSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, chartName, true);
>      fStream.close();
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | The shape collection to which the chart will be added. |
| x | float | The X coordinate for positioning the chart. |
| y | float | The Y coordinate for positioning the chart. |
| workbookStream | java.io.InputStream | A stream containing the workbook data. |
| worksheetName | java.lang.String | The name of the worksheet that contains the chart. |
| chartName | java.lang.String | The name of the chart to be added. |
| embedAllWorkbook | boolean | If true, the entire workbook will be embedded in the chart; if false, only the chart data will be embedded. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - The chart that was added to the shape collection.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```


Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | The shape collection to which the chart will be added. |
| x | float | The X coordinate for positioning the chart. |
| y | float | The Y coordinate for positioning the chart. |
| workbookPath | java.lang.String | The file path to the workbook containing the chart. |
| worksheetName | java.lang.String | The name of the worksheet that contains the chart. |
| chartName | java.lang.String | The name of the chart to be added. |
| embedWorkbook | boolean | If true, the workbook will be embedded in the chart; if false, the chart will link to the external workbook. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - The chart that was added to the shape collection.
