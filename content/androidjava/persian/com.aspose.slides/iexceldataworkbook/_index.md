---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: نمایش‌گر یک دفترکار که دسترسی به داده‌های اکسل را برای استفاده عمومی فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

نمایش‌گر یک دفترکار که دسترسی به داده‌های اکسل را برای استفاده عمومی فراهم می‌کند.
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


Retrieves a collection of cells from the workbook that match the specified formula.

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
| formula | java.lang.String | یک فرمول یا عبارت بازه (مثلاً "Sheet1!A1:B3") برای شناسایی سلول‌های هدف. |
| skipHiddenCells | boolean | اگر مقدار true باشد، سلول‌های مخفی (مثلاً در ردیف‌ها یا ستون‌های مخفی) از نتیجه حذف می‌شوند. |

**بازگرداندن:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - یک لیست فقط-خواندنی از سلول‌ها که با فرمول مشخص مطابقت دارند.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


Retrieves a cell from the specified worksheet using its index and cell coordinates.

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
| worksheetIndex | int | اندیس صفر-پایهٔ کاربرگ. |
| row | int | اندیس صفر-پایهٔ ردیف سلول. |
| column | int | اندیس صفر-پایهٔ ستون سلول. |

**بازگرداندن:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - سلول در مکان مشخص شده.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```


Retrieves a cell from the specified worksheet using its name and cell coordinates.

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
| row | int | اندیس صفر-پایهٔ ردیف سلول. |
| column | int | اندیس صفر-پایهٔ ستون سلول. |

**بازگرداندن:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - سلول در مکان مشخص شده.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```


Retrieves a cell from the specified worksheet using its index and Excel-style cell name (e.g., "B2").

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
| worksheetIndex | int | اندیس صفر-پایهٔ کاربرگ. |
| cellName | java.lang.String | مرجع سلولی به سبک اکسل (مثلاً "A1"، "C5"). |

**بازگرداندن:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - سلول در مکان مشخص شده.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```


Retrieves a cell from the specified worksheet using Excel-style cell name (e.g., "B2").

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
| cellName | java.lang.String | مرجع سلولی به سبک اکسل (مثلاً "A1"، "C5"). |

**بازگرداندن:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - سلول در مکان مشخص شده.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


Retrieves a dictionary containing the indexes and names of all charts in the specified worksheet of an Excel workbook.

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

**بازگرداندن:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - یک لغت‌نامه که کلید آن اندیس نمودار و مقدار آن نام نمودار است.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```


Retrieves the names of all worksheets contained in the Excel workbook.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**بازگرداندن:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - یک لیست از نام‌های کاربرگ‌ها