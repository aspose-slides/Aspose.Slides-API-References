---
title: IExcelDataWorkbook
second_title: Aspose.Slides برای Java مرجع API
description: نمایانگر یک کتاب‌کار است که دسترسی به داده‌های Excel را برای استفاده عمومی فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

نمایانگر یک کتاب‌کار است که دسترسی به داده‌های Excel را برای استفاده عمومی فراهم می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Retrieves a collection of cells from the workbook that match the specified formula. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Retrieves a cell from the specified worksheet using its index and cell coordinates. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Retrieves a cell from the specified worksheet using its name and cell coordinates. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Retrieves a cell from the specified worksheet using its index and Excel-style cell name (e.g., "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Retrieves a cell from the specified worksheet using Excel-style cell name (e.g., "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Retrieves a dictionary containing the indexes and names of all charts in the specified worksheet of an Excel workbook. |
| [getWorksheetNames()](#getWorksheetNames--) | Retrieves the names of all worksheets contained in the Excel workbook. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

مجموعه‌ای از سلول‌ها را از کتاب‌کار دریافت می‌کند که با فرمول مشخص شده مطابقت دارند.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //خروجی: 5
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| formula | java.lang.String | یک فرمول یا عبارت بازه (مثلاً "Sheet1!A1:B3") که برای شناسایی سلول‌های هدف استفاده می‌شود. |
| skipHiddenCells | boolean | اگر true باشد، سلول‌های مخفی (مثلاً در ردیف‌ها یا ستون‌های مخفی) از نتیجه حذف می‌شوند. |

**بازگشت:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - یک لیست فقط-خواندنی از سلول‌ها که با فرمول مشخص شده مطابقت دارند.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

یک سلول را از کاربرگ مشخص‌شده با استفاده از شاخص و مختصات سلول دریافت می‌کند.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetIndex | int | شاخص صفر-پایهٔ کاربرگ. |
| row | int | شاخص صفر-پایهٔ ردیف سلول. |
| column | int | شاخص صفر-پایهٔ ستون سلول. |

**بازگشت:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - سلول در موقعیت مشخص‌شده.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```

یک سلول را از کاربرگ مشخص‌شده با استفاده از نام و مختصات سلول دریافت می‌کند.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetName | java.lang.String | نام کاربرگ. |
| row | int | شاخص صفر-پایهٔ ردیف سلول. |
| column | int | شاخص صفر-پایهٔ ستون سلول. |

**بازگشت:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - سلول در موقعیت مشخص‌شده.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```

یک سلول را از کاربرگ مشخص‌شده با استفاده از شاخص و نام سلول به-صورت-اکسل (مثلاً "B2") دریافت می‌کند.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetIndex | int | شاخص صفر-پایهٔ کاربرگ. |
| cellName | java.lang.String | ارجاع سلول به-صورت-اکسل (مثلاً "A1"، "C5"). |

**بازگشت:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - سلول در موقعیت مشخص‌شده.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```

یک سلول را از کاربرگ مشخص‌شده با استفاده از نام سلول به-صورت-اکسل (مثلاً "B2") دریافت می‌کند.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetName | java.lang.String | نام کاربرگ. |
| cellName | java.lang.String | ارجاع سلول به-صورت-اکسل (مثلاً "A1"، "C5"). |

**بازگشت:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - سلول در موقعیت مشخص‌شده.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

یک دیکشنری شامل شاخص‌ها و نام‌های تمام نمودارها در کاربرگ مشخص‌شدهٔ یک کتاب‌کار اکسل بازیابی می‌کند.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Dictionary.Enumerator<Integer, String> sheetCharts = wb.getChartsFromWorksheet("worksheetName").iterator();
>  while (sheetCharts.hasNext())
>  {
>      KeyValuePair<Integer, String> chart = sheetCharts.next();
>      System.out.println(chart.getKey() + " : " + chart.getValue());
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetName | java.lang.String | نام کاربرگی که نمودارها در آن جستجو می‌شوند. |

**بازگشت:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - یک دیکشنری که کلید آن شاخص نمودار و مقدار آن نام نمودار است.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```

نام‌های تمام کاربرگ‌های موجود در کتاب‌کار اکسل را بازیابی می‌کند.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**بازگشت:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - یک لیست از نام‌های کاربرگ‌ها