---
title: IChartDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: دسترسی به کتاب کار Excel جاسازی شده را فراهم می‌کند
type: docs
url: /fa/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

دسترسی به کتاب کار Excel جاسازی شده را فراهم می‌کند
## متدها

| Method | Description |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | تمام فرمول‌های موجود در کتاب کار را محاسبه کرده و مقادیر سلول‌های مربوطه را به‌روز می‌کند. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | مجموعه‌ای از سلول‌ها را دریافت می‌کند. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | سلولی را که می‌تواند برای سری‌های نمودار یا دسته‌بندی‌ها استفاده شود دریافت می‌کند. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | سلولی را که می‌تواند برای سری‌های نمودار یا دسته‌بندی‌ها استفاده شود دریافت می‌کند. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | سلولی را که می‌تواند برای سری‌های نمودار یا دسته‌بندی‌ها استفاده شود دریافت می‌کند. |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | سلولی را که می‌تواند برای سری‌های نمودار یا دسته‌بندی‌ها استفاده شود دریافت می‌کند. |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | سلولی را که می‌تواند برای سری‌های نمودار یا دسته‌بندی‌ها استفاده شود دریافت می‌کند. |
| [clear(int sheetIndex)](#clear-int-) | تمام مقادیر سلول‌ها را در شیت پاک می‌کند. |
| [getWorksheets()](#getWorksheets--) | یک مجموعه از کاربرگ‌ها را دریافت می‌کند. |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```

تمام فرمول‌های موجود در کتاب کار را محاسبه کرده و مقادیر سلول‌های مربوطه را به‌روز می‌کند.

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

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public abstract IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

مجموعه‌ای از سلول‌ها را دریافت می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | فرمول Excel مانند "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | اگر مقدار true باشد، متد مجموعه‌ای بدون سلول‌های مخفی را برمی‌گرداند. |

**بازگشت:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - مجموعه‌ای از سلول‌ها [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```

سلولی را که می‌تواند برای سری‌های نمودار یا دسته‌بندی‌ها استفاده شود دریافت می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | نام کاربرگ. |
| row | int | سطر. |
| column | int | ستون. |

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell شی
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```

سلولی را که می‌تواند برای سری‌های نمودار یا دسته‌بندی‌ها استفاده شود دریافت می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | اندیس کاربرگ. |
| row | int | سطر. |
| column | int | ستون. |

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell شی
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```

سلولی را که می‌تواند برای سری‌های نمودار یا دسته‌بندی‌ها استفاده شود دریافت می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | اندیس کاربرگ. |
| cellName | java.lang.String | نام سلول. |

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell شی
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

سلولی را که می‌تواند برای سری‌های نمودار یا دسته‌بندی‌ها استفاده شود دریافت می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | اندیس کاربرگ. |
| cellName | java.lang.String | نام سلول. |
| value | java.lang.Object | مقدار. |

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell شی
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

سلولی را که می‌تواند برای سری‌های نمودار یا دسته‌بندی‌ها استفاده شود دریافت می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | اندیس کاربرگ. |
| row | int | سطر. |
| column | int | ستون. |
| value | java.lang.Object | مقدار. |

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell شی
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```

تمام مقادیر سلول‌ها را در شیت پاک می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| sheetIndex | int | اندیس شیت |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
```

یک مجموعه از کاربرگ‌ها را دریافت می‌کند.

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

**بازگشت:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)