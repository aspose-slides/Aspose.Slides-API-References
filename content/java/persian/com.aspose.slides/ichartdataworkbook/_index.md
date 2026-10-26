---
title: IChartDataWorkbook
second_title: Aspose.Slides for Java API Reference
description: دسترسی به دفتر کاری Excel تعبیه‌شده را فراهم می‌کند
type: docs
url: /fa/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

دسترسی به دفتر کاری Excel تعبیه‌شده را فراهم می‌کند
## متدها

| متد | توضیح |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | تمام فرمول‌های موجود در دفتر کاری را محاسبه کرده و مقادیر سلول‌های مرتبط را به‌روزرسانی می‌کند. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | مجموعه‌ای از سلول‌ها را دریافت می‌کند. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود. |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود. |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود. |
| [clear(int sheetIndex)](#clear-int-) | تمام مقادیر سلول‌ها را در شیت پاک می‌کند. |
| [getWorksheets()](#getWorksheets--) | یک collection از Worksheets را دریافت می‌کند. |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```

تمام فرمول‌های موجود در دفتر کاری را محاسبه کرده و مقادیر سلول‌های مرتبط را به‌روزرسانی می‌کند.

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
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| formula | java.lang.String | فرمول Excel مانند "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | اگر true باشد، متد مجموعه‌ای بدون سلول‌های مخفی را برمی‌گرداند. |

**بازگشت:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - مجموعه‌ای از سلول‌ها [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```

سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetName | java.lang.String | نام worksheet. |
| row | int | سطر. |
| column | int | ستون. |

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell شی
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```

سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetIndex | int | اندیس worksheet. |
| row | int | سطر. |
| column | int | ستون. |

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell شی
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```

سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetIndex | int | اندیس worksheet. |
| cellName | java.lang.String | نام سلول. |

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell شی
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetIndex | int | اندیس worksheet. |
| cellName | java.lang.String | نام سلول. |
| value | java.lang.Object | مقدار. |

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell شی
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

سلولی را دریافت می‌کند که می‌تواند برای سری‌های نمودار یا دسته‌ها استفاده شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetIndex | int | اندیس worksheet. |
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
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sheetIndex | int | اندیس شیت |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
```

یک collection از Worksheets را دریافت می‌کند.

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