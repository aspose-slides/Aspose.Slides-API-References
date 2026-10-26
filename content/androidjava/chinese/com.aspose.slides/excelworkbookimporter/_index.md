---
title: ExcelWorkbookImporter
second_title: Aspose.Slides Android 通过 Java API 参考
description: 提供将 Excel 工作簿内容导入到演示文稿的功能。
type: docs
url: /zh/com.aspose.slides/excelworkbookimporter/
---
**继承:**  
java.lang.Object
```
public class ExcelWorkbookImporter
```

提供将 Excel 工作簿内容导入到演示文稿的功能。

## 方法

| 方法 | 描述 |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | 从指定的 Excel 工作簿检索图表，并将其添加到给定形状集合的末尾，位于指定的坐标处。 |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | 从指定的 Excel 工作簿检索图表，并将其添加到给定形状集合的末尾，位于指定的坐标处。 |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | 从指定的 Excel 工作簿检索图表，并将其添加到给定形状集合的末尾，位于指定的坐标处。 |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | 从指定的 Excel 工作簿检索图表，并将其添加到给定形状集合的末尾，位于指定的坐标处。 |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | 从指定的 Excel 工作簿检索表格，并将其添加到给定形状集合的末尾，位于指定的坐标处。 |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | 从指定的 Excel 工作簿检索表格，并将其添加到给定形状集合的末尾，位于指定的坐标处。 |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | 从指定的 Excel 工作簿检索表格，并将其添加到给定形状集合的末尾，位于指定的坐标处。 |

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

从指定的 Excel 工作簿检索图表，并将其添加到给定形状集合的末尾，位于指定的坐标处。

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
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

Retrieves a table from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates.

--------------------

> ```
> IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbook, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | The shape collection to which the table will be added. |
| x | float | The X coordinate for positioning the table. |
| y | float | The Y coordinate for positioning the table. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | The Excel workbook. |
| worksheetName | java.lang.String | The name of the worksheet that contains the table. |
| cellRange | java.lang.String | The cell range that defines the table (for example, "A1:D10"). |

**Returns:**
[ITable](../../com.aspose.slides/itable) - The table that was added to the shape collection.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

Retrieves a table from the specified Excel workbook file and adds it to the end of the given shape collection at the specified coordinates.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | The shape collection to which the table will be added. |
| x | float | The X coordinate for positioning the table. |
| y | float | The Y coordinate for positioning the table. |
| workbookPath | java.lang.String | The path to the Excel workbook file. |
| worksheetName | java.lang.String | The name of the worksheet that contains the table. |
| cellRange | java.lang.String | The cell range that defines the table (for example, "A1:D10"). |

**Returns:**
[ITable](../../com.aspose.slides/itable) - The table that was added to the shape collection.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)

从指定的 Excel 工作簿文件检索表格，并将其添加到给定形状集合的末尾，位于指定的坐标处。

--------------------

> ```
> FileInputStream fStream = new FileInputStream(workbookPath);
> Presentation pres = new Presentation();
> try {
>     ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, "A1:D10");
>     pres.save("result.pptx", SaveFormat.Pptx);
> } finally {
>     if (pres != null) pres.dispose();
> }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 要将表格添加到的形状集合。 |
| x | float | 表格定位的 X 坐标。 |
| y | float | 表格定位的 Y 坐标。 |
| workbookStream | java.io.InputStream | 包含工作簿数据的流。 |
| worksheetName | java.lang.String | 包含表格的工作表名称。 |
| cellRange | java.lang.String | 定义表格的单元格范围（例如 "A1:D10"）。 |

**返回:**
[ITable](../../com.aspose.slides/itable) - 已添加到形状集合的表格。