---
title: ChartDataWorkbook
second_title: مرجع API Aspose.Slides برای Java
description: دسترسی به ورک‌بوک Excel توکار را فراهم می‌کند
type: docs
url: /fa/com.aspose.slides/chartdataworkbook/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)  
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

دسترسی به ورک‌بوک Excel توکار را فراهم می‌کند

## Methods

| Method | Description |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | یک مجموعه از ورک‌شیت‌ها را دریافت می‌کند. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | مجموعه‌ای از سلول‌ها را دریافت می‌کند. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود |
| [clear(int sheetIndex)](#clear-int-) | تمام مقادیر سلول‌ها را در برگه پاک می‌کند |
| [calculateFormulas()](#calculateFormulas--) | تمام فرمول‌ها را در ورک‌بوک محاسبه می‌کند و مقادیر سلول‌های مربوطه را به‌روز می‌سازد. |
### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```

یک مجموعه از ورک‌شیت‌ها را دریافت می‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**  
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)
### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

مجموعه‌ای از سلول‌ها را دریافت می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | فرمول Excel مانند "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | اگر true باشد، متد مجموعه‌ای بدون سلول‌های مخفی را بازمی‌گرداند. |

**Returns:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```

سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | نام ورک‌شیت. |
| row | int | ردیف. |
| column | int | ستون. |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell شی
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```

سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | اندیس ورک‌شیت. |
| row | int | ردیف. |
| column | int | ستون. |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell شی
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```

سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | اندیس ورک‌شیت. |
| cellName | java.lang.String | نام سلول. |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell شی
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | اندیس ورک‌شیت. |
| cellName | java.lang.String | نام سلول. |
| value | java.lang.Object | مقدار. |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell شی
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | اندیس ورک‌شیت. |
| row | int | ردیف. |
| column | int | ستون. |
| value | java.lang.Object | مقدار. |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell شی
### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```

تمام مقادیر سلول‌ها را در برگه پاک می‌کند

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sheetIndex | int | اندیس برگه |
### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```

تمام فرمول‌ها را در ورک‌بوک محاسبه می‌کند و مقادیر سلول‌های مربوطه را به‌روز می‌سازد.

--------------------

> ```
> Example shows how to assign a formula to the cell and to calculate a value. The value of the "B4" cell is getting set to 5.
>   
>   Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 100, 100, 300, 400);
>       IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>       wb.getCell(0, "B2", 2);
>       wb.getCell(0, "B3", 3);
>       wb.getCell(0, "B4").setFormula("B2+B3");
>       wb.calculateFormulas();
>       ...
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```