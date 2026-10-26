---
title: ExcelWorkbookImporter
second_title: Aspose.Slides for Java API 參考
description: 提供將 Excel 活頁簿的內容匯入至簡報的功能。
type: docs
url: /zh-hant/com.aspose.slides/excelworkbookimporter/
---
**Inheritance:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

提供從 Excel 活頁簿匯入內容至簡報的功能。
## 方法

| 方法 | 說明 |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | 從指定的 Excel 活頁簿取得圖表，並依指定座標將其新增至給定圖形集合的末端。 |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | 從指定的 Excel 活頁簿取得圖表，並依指定座標將其新增至給定圖形集合的末端。 |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | 從指定的 Excel 活頁簿取得圖表，並依指定座標將其新增至給定圖形集合的末端。 |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | 從指定的 Excel 活頁簿取得圖表，並依指定座標將其新增至給定圖形集合的末端。 |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | 從指定的 Excel 活頁簿取得表格，並依指定座標將其新增至給定圖形集合的末端。 |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | 從指定的 Excel 活頁簿檔案取得表格，並依指定座標將其新增至給定圖形集合的末端。 |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | 從指定的 Excel 活頁簿檔案取得表格，並依指定座標將其新增至給定圖形集合的末端。 |

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

從指定的 Excel 活頁簿取得圖表，並依指定座標將其新增至給定圖形集合的末端。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 將要新增圖表的圖形集合。 |
| x | float | 圖表定位的 X 座標。 |
| y | float | 圖表定位的 Y 座標。 |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel 活頁簿。 |
| worksheetName | java.lang.String | 包含圖表的工作表名稱。 |
| chartIndex | int | 圖表形狀的零基索引。可使用 [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-) 方法取得此索引。 |
| embedAllWorkbook | boolean | 若為 true，整個活頁簿將嵌入圖表；若為 false，僅嵌入圖表資料。 |

**返回值:**
[IChart](../../com.aspose.slides/ichart) - 已新增至圖形集合的圖表。

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

從指定的 Excel 活頁簿取得圖表，並依指定座標將其新增至給定圖形集合的末端。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 將要新增圖表的圖形集合。 |
| x | float | 圖表定位的 X 座標。 |
| y | float | 圖表定位的 Y 座標。 |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel 活頁簿。 |
| worksheetName | java.lang.String | 包含圖表的工作表名稱。 |
| chartName | java.lang.String | 要新增的圖表名稱。 |
| embedAllWorkbook | boolean | 若為 true，整個活頁簿將嵌入圖表；若為 false，僅嵌入圖表資料。 |

**返回值:**
[IChart](../../com.aspose.slides/ichart) - 已新增至圖形集合的圖表。

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

從指定的 Excel 活頁簿取得圖表，並依指定座標將其新增至給定圖形集合的末端。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 將要新增圖表的圖形集合。 |
| x | float | 圖表定位的 X 座標。 |
| y | float | 圖表定位的 Y 座標。 |
| workbookStream | java.io.InputStream | 含有活頁簿資料的串流。 |
| worksheetName | java.lang.String | 包含圖表的工作表名稱。 |
| chartName | java.lang.String | 要新增的圖表名稱。 |
| embedAllWorkbook | boolean | 若為 true，整個活頁簿將嵌入圖表；若為 false，僅嵌入圖表資料。 |

**返回值:**
[IChart](../../com.aspose.slides/ichart) - 已新增至圖形集合的圖表。

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

從指定的 Excel 活頁簿取得圖表，並依指定座標將其新增至給定圖形集合的末端。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 將要新增圖表的圖形集合。 |
| x | float | 圖表定位的 X 座標。 |
| y | float | 圖表定位的 Y 座標。 |
| workbookPath | java.lang.String | 含有圖表之活頁簿的檔案路徑。 |
| worksheetName | java.lang.String | 包含圖表的工作表名稱。 |
| chartName | java.lang.String | 要新增的圖表名稱。 |
| embedWorkbook | boolean | 若為 true，活頁簿將嵌入圖表；若為 false，圖表將連結至外部活頁簿。 |

**返回值:**
[IChart](../../com.aspose.slides/ichart) - 已新增至圖形集合的圖表。

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

從指定的 Excel 活頁簿取得表格，並依指定座標將其新增至給定圖形集合的末端。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 將要新增表格的圖形集合。 |
| x | float | 表格定位的 X 座標。 |
| y | float | 表格定位的 Y 座標。 |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel 活頁簿。 |
| worksheetName | java.lang.String | 包含表格的工作表名稱。 |
| cellRange | java.lang.String | 定義表格的儲存格範圍（例如 "A1:D10"）。 |

**返回值:**
[ITable](../../com.aspose.slides/itable) - 已新增至圖形集合的表格。

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

從指定的 Excel 活頁簿檔案取得表格，並依指定座標將其新增至給定圖形集合的末端。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 將要新增表格的圖形集合。 |
| x | float | 表格定位的 X 座標。 |
| y | float | 表格定位的 Y 座標。 |
| workbookPath | java.lang.String | Excel 活頁簿檔案的路徑。 |
| worksheetName | java.lang.String | 包含表格的工作表名稱。 |
| cellRange | java.lang.String | 定義表格的儲存格範圍（例如 "A1:D10"）。 |

**返回值:**
[ITable](../../com.aspose.slides/itable) - 已新增至圖形集合的表格。

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

從指定的 Excel 活頁簿檔案取得表格，並依指定座標將其新增至給定圖形集合的末端。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 將要新增表格的圖形集合。 |
| x | float | 表格定位的 X 座標。 |
| y | float | 表格定位的 Y 座標。 |
| workbookStream | java.io.InputStream | 含有活頁簿資料的串流。 |
| worksheetName | java.lang.String | 包含表格的工作表名稱。 |
| cellRange | java.lang.String | 定義表格的儲存格範圍（例如 "A1:D10"）。 |

**返回值:**
[ITable](../../com.aspose.slides/itable) - 已新增至圖形集合的表格。