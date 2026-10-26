---
title: ChartDataWorkbook
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: دسترسی به کتاب‌کار Excel توکار را فراهم می‌کند
type: docs
url: /fa/com.aspose.slides/chartdataworkbook/
---
**وراثت:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

دسترسی به کتاب کار Excel توکار را فراهم می‌کند
## متدها

| متد | توضیحات |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | مجموعه‌ای از ورق‌های کار را دریافت می‌کند. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | مجموعه سلول‌ها را دریافت می‌کند. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | سلولی را که می‌توان برای سری‌ها یا دسته‌های نمودار استفاده کرد، دریافت می‌کند |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | سلولی را که می‌توان برای سری‌ها یا دسته‌های نمودار استفاده کرد، دریافت می‌کند |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | سلولی را که می‌توان برای سری‌ها یا دسته‌های نمودار استفاده کرد، دریافت می‌کند |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | سلولی را که می‌توان برای سری‌ها یا دسته‌های نمودار استفاده کرد، دریافت می‌کند |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | سلولی را که می‌توان برای سری‌ها یا دسته‌های نمودار استفاده کرد، دریافت می‌کند |
| [clear(int sheetIndex)](#clear-int-) | تمام مقادیر سلول‌ها را در برگه پاک می‌کند |
| [calculateFormulas()](#calculateFormulas--) | تمام فرمول‌ها را در کتاب کار محاسبه می‌کند و مقادیر سلول‌های مربوطه را به‌روز می‌کند. |

### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```

مجموعه‌ای از ورق‌های کار را دریافت می‌کند.

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
### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

مجموعه سلول‌ها را دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| formula | java.lang.String | فرمول Excel مانند "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | اگر true باشد، متد مجموعه‌ای بدون سلول‌های مخفی را برمی‌گرداند. |

**بازگشت:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```

سلولی را که می‌توان برای سری‌ها یا دسته‌های نمودار استفاده کرد، دریافت می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetName | java.lang.String | نام ورق کار. |
| row | int | سطر. |
| column | int | ستون. |

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```

سلولی را که می‌توان برای سری‌ها یا دسته‌های نمودار استفاده کرد، دریافت می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetIndex | int | ایندکس ورق کار. |
| row | int | سطر. |
| column | int | ستون. |

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```

سلولی را که می‌توان برای سری‌ها یا دسته‌های نمودار استفاده کرد، دریافت می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetIndex | int | ایندکس ورق کار. |
| cellName | java.lang.String | نام سلول. |

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

سلولی را که می‌توان برای سری‌ها یا دسته‌های نمودار استفاده کرد، دریافت می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetIndex | int | ایندکس ورق کار. |
| cellName | java.lang.String | نام سلول. |
| value | java.lang.Object | مقدار. |

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

سلولی را که می‌توان برای سری‌ها یا دسته‌های نمودار استفاده کرد، دریافت می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetIndex | int | ایندکس ورق کار. |
| row | int | سطر. |
| column | int | ستون. |
| value | java.lang.Object | مقدار. |

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```

تمام مقادیر سلول‌ها را در برگه پاک می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sheetIndex | int | ایندکس برگه |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```

تمام فرمول‌ها را در کتاب کار محاسبه می‌کند و مقادیر سلول‌های مربوطه را به‌روز می‌کند.

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