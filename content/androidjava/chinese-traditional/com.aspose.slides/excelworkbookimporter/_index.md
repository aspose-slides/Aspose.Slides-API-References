---
title: ExcelWorkbookImporter
second_title: Aspose.Slides 適用於 Android 的 Java API 參考
description: 提供將 Excel 工作簿內容匯入至簡報的功能。
type: docs
url: /zh-hant/com.aspose.slides/excelworkbookimporter/
---
**繼承：**
java.lang.Object
```
public class ExcelWorkbookImporter
```

提供從 Excel 工作簿匯入內容至簡報的功能。

## 方法

| 方法 | 說明 |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | 從指定的 Excel 工作簿檢索圖表，並將其添加到給定形狀集合的末尾，位於指定座標。 |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | 從指定的 Excel 工作簿檢索圖表，並將其添加到給定形狀集合的末尾，位於指定座標。 |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | 從指定的 Excel 工作簿檢索圖表，並將其添加到給定形狀集合的末尾，位於指定座標。 |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | 從指定的 Excel 工作簿檢索圖表，並將其添加到給定形狀集合的末尾，位於指定座標。 |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | 從指定的 Excel 工作簿檢索表格，並將其添加到給定形狀集合的末尾，位於指定座標。 |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | 從指定的 Excel 工作簿檔案檢索表格，並將其添加到給定形狀集合的末尾，位於指定座標。 |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | 從指定的 Excel 工作簿檔案檢索表格，並將其添加到給定形狀集合的末尾，位於指定座標。 |

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

從指定的 Excel 工作簿檢索圖表，並將其添加到給定形狀集合的末尾，位於指定座標。

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 要加入圖表的形狀集合。 |
| x | float | 圖表定位的 X 坐標。 |
| y | float | 圖表定位的 Y 坐標。 |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel 工作簿。 |
| worksheetName | java.lang.String | 包含圖表的工作表名稱。 |
| chartIndex | int | 要插入的圖表形狀的零基索引。可使用 [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-) 方法取得此索引。 |
| embedAllWorkbook | boolean | 如果為 true，整個工作簿將嵌入圖表；如果為 false，僅嵌入圖表資料。 |

**傳回:**  
[IChart](../../com.aspose.slides/ichart) - 已加入形狀集合的圖表。

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

從指定的 Excel 工作簿檢索圖表，並將其添加到給定形狀集合的末尾，位於指定座標。

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 要加入圖表的形狀集合。 |
| x | float | 圖表定位的 X 坐標。 |
| y | float | 圖表定位的 Y 坐標。 |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel 工作簿。 |
| worksheetName | java.lang.String | 包含圖表的工作表名稱。 |
| chartName | java.lang.String | 要加入的圖表名稱。 |
| embedAllWorkbook | boolean | 如果為 true，整個工作簿將嵌入圖表；如果為 false，僅嵌入圖表資料。 |

**傳回:**  
[IChart](../../com.aspose.slides/ichart) - 已加入形狀集合的圖表。

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

從指定的 Excel 工作簿檢索圖表，並將其添加到給定形狀集合的末尾，位於指定座標。

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 要加入圖表的形狀集合。 |
| x | float | 圖表定位的 X 坐標。 |
| y | float | 圖表定位的 Y 坐標。 |
| workbookStream | java.io.InputStream | 含有工作簿資料的串流。 |
| worksheetName | java.lang.String | 包含圖表的工作表名稱。 |
| chartName | java.lang.String | 要加入的圖表名稱。 |
| embedAllWorkbook | boolean | 如果為 true，整個工作簿將嵌入圖表；如果為 false，僅嵌入圖表資料。 |

**傳回:**  
[IChart](../../com.aspose.slides/ichart) - 已加入形狀集合的圖表。

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

從指定的 Excel 工作簿檢索圖表，並將其添加到給定形狀集合的末尾，位於指定座標。

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 要加入圖表的形狀集合。 |
| x | float | 圖表定位的 X 坐標。 |
| y | float | 圖表定位的 Y 坐標。 |
| workbookPath | java.lang.String | 包含圖表之工作簿的檔案路徑。 |
| worksheetName | java.lang.String | 包含圖表的工作表名稱。 |
| chartName | java.lang.String | 要加入的圖表名稱。 |
| embedWorkbook | boolean | 如果為 true，工作簿將嵌入圖表；如果為 false，圖表將連結至外部工作簿。 |

**傳回:**  
[IChart](../../com.aspose.slides/ichart) - 已加入形狀集合的圖表。

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

從指定的 Excel 工作簿檢索表格，並將其添加到給定形狀集合的末尾，位於指定座標。

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 要加入表格的形狀集合。 |
| x | float | 表格定位的 X 坐標。 |
| y | float | 表格定位的 Y 坐標。 |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel 工作簿。 |
| worksheetName | java.lang.String | 包含表格的工作表名稱。 |
| cellRange | java.lang.String | 定義表格的儲存格範圍（例如 "A1:D10"）。 |

**傳回:**  
[ITable](../../com.aspose.slides/itable) - 已加入形狀集合的表格。

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

從指定的 Excel 工作簿檔案檢索表格，並將其添加到給定形狀集合的末尾，位於指定座標。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 要加入表格的形狀集合。 |
| x | float | 表格定位的 X 坐標。 |
| y | float | 表格定位的 Y 坐標。 |
| workbookPath | java.lang.String | Excel 工作簿檔案的路徑。 |
| worksheetName | java.lang.String | 包含表格的工作表名稱。 |
| cellRange | java.lang.String | 定義表格的儲存格範圍（例如 "A1:D10"）。 |

**傳回:**  
[ITable](../../com.aspose.slides/itable) - 已加入形狀集合的表格。

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

從指定的 Excel 工作簿檔案檢索表格，並將其添加到給定形狀集合的末尾，位於指定座標。

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 要加入表格的形狀集合。 |
| x | float | 表格定位的 X 坐標。 |
| y | float | 表格定位的 Y 坐標。 |
| workbookStream | java.io.InputStream | 含有工作簿資料的串流。 |
| worksheetName | java.lang.String | 包含表格的工作表名稱。 |
| cellRange | java.lang.String | 定義表格的儲存格範圍（例如 "A1:D10"）。 |

**傳回:**  
[ITable](../../com.aspose.slides/itable) - 已加入形狀集合的表格。