---
title: ExcelWorkbookImporter
second_title: Aspose.Slides for Java API 参考
description: 提供从 Excel 工作簿导入内容到演示文稿的功能。
type: docs
url: /zh/com.aspose.slides/excelworkbookimporter/
---
**继承:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

提供将 Excel 工作簿中的内容导入到演示文稿的功能。

## 方法

| 方法 | 描述 |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | 检索指定 Excel 工作簿中的图表，并将其添加到给定形状集合的末尾，位于指定坐标。 |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | 检索指定 Excel 工作簿中的图表，并将其添加到给定形状集合的末尾，位于指定坐标。 |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | 检索指定 Excel 工作簿中的图表，并将其添加到给定形状集合的末尾，位于指定坐标。 |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | 检索指定 Excel 工作簿中的图表，并将其添加到给定形状集合的末尾，位于指定坐标。 |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | 检索指定 Excel 工作簿中的表格，并将其添加到给定形状集合的末尾，位于指定坐标。 |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | 检索指定 Excel 工作簿文件中的表格，并将其添加到给定形状集合的末尾，位于指定坐标。 |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | 检索指定 Excel 工作簿文件中的表格，并将其添加到给定形状集合的末尾，位于指定坐标。 |

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

检索指定 Excel 工作簿中的图表，并将其添加到给定形状集合的末尾，位于指定坐标。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 将添加图表的形状集合。 |
| x | float | 用于定位图表的 X 坐标。 |
| y | float | 用于定位图表的 Y 坐标。 |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel 工作簿。 |
| worksheetName | java.lang.String | 包含图表的工作表名称。 |
| chartIndex | int | 要插入的图表形状的零基索引。可使用 [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-) 方法获取此索引。 |
| embedAllWorkbook | boolean | 为 true 时，将整个工作簿嵌入图表；为 false 时，仅嵌入图表数据。 |

**返回值:**
[IChart](../../com.aspose.slides/ichart) - 已添加到形状集合的图表。

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

检索指定 Excel 工作簿中的图表，并将其添加到给定形状集合的末尾，位于指定坐标。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 将添加图表的形状集合。 |
| x | float | 用于定位图表的 X 坐标。 |
| y | float | 用于定位图表的 Y 坐标。 |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel 工作簿。 |
| worksheetName | java.lang.String | 包含图表的工作表名称。 |
| chartName | java.lang.String | 要添加的图表名称。 |
| embedAllWorkbook | boolean | 为 true 时，将整个工作簿嵌入图表；为 false 时，仅嵌入图表数据。 |

**返回值:**
[IChart](../../com.aspose.slides/ichart) - 已添加到形状集合的图表。

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

检索指定 Excel 工作簿中的图表，并将其添加到给定形状集合的末尾，位于指定坐标。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 将添加图表的形状集合。 |
| x | float | 用于定位图表的 X 坐标。 |
| y | float | 用于定位图表的 Y 坐标。 |
| workbookStream | java.io.InputStream | 包含工作簿数据的流。 |
| worksheetName | java.lang.String | 包含图表的工作表名称。 |
| chartName | java.lang.String | 要添加的图表名称。 |
| embedAllWorkbook | boolean | 为 true 时，将整个工作簿嵌入图表；为 false 时，仅嵌入图表数据。 |

**返回值:**
[IChart](../../com.aspose.slides/ichart) - 已添加到形状集合的图表。

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

检索指定 Excel 工作簿中的图表，并将其添加到给定形状集合的末尾，位于指定坐标。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 将添加图表的形状集合。 |
| x | float | 用于定位图表的 X 坐标。 |
| y | float | 用于定位图表的 Y 坐标。 |
| workbookPath | java.lang.String | 包含图表的工作簿文件路径。 |
| worksheetName | java.lang.String | 包含图表的工作表名称。 |
| chartName | java.lang.String | 要添加的图表名称。 |
| embedWorkbook | boolean | 为 true 时，工作簿将嵌入图表；为 false 时，图表将链接到外部工作簿。 |

**返回值:**
[IChart](../../com.aspose.slides/ichart) - 已添加到形状集合的图表。

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

检索指定 Excel 工作簿中的表格，并将其添加到给定形状集合的末尾，位于指定坐标。

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


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 将添加表格的形状集合。 |
| x | float | 用于定位表格的 X 坐标。 |
| y | float | 用于定位表格的 Y 坐标。 |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel 工作簿。 |
| worksheetName | java.lang.String | 包含表格的工作表名称。 |
| cellRange | java.lang.String | 定义表格的单元格范围（例如 "A1:D10"）。 |

**返回值:**
[ITable](../../com.aspose.slides/itable) - 已添加到形状集合的表格。

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

检索指定 Excel 工作簿文件中的表格，并将其添加到给定形状集合的末尾，位于指定坐标。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 将添加表格的形状集合。 |
| x | float | 用于定位表格的 X 坐标。 |
| y | float | 用于定位表格的 Y 坐标。 |
| workbookPath | java.lang.String | Excel 工作簿文件的路径。 |
| worksheetName | java.lang.String | 包含表格的工作表名称。 |
| cellRange | java.lang.String | 定义表格的单元格范围（例如 "A1:D10"）。 |

**返回值:**
[ITable](../../com.aspose.slides/itable) - 已添加到形状集合的表格。

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

检索指定 Excel 工作簿文件中的表格，并将其添加到给定形状集合的末尾，位于指定坐标。

--------------------

> ```
> FileInputStream fStream = new FileInputStream(workbookPath);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 将添加表格的形状集合。 |
| x | float | 用于定位表格的 X 坐标。 |
| y | float | 用于定位表格的 Y 坐标。 |
| workbookStream | java.io.InputStream | 包含工作簿数据的流。 |
| worksheetName | java.lang.String | 包含表格的工作表名称。 |
| cellRange | java.lang.String | 定义表格的单元格范围（例如 "A1:D10"）。 |

**返回值:**
[ITable](../../com.aspose.slides/itable) - 已添加到形状集合的表格。