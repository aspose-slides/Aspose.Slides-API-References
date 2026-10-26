---
title: ExcelDataWorkbook
second_title: Aspose.Slides برای جاوا مرجع API
description: یک کتاب‌کار را نشان می‌دهد که دسترسی به داده‌های Excel را برای استفاده عمومی فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/exceldataworkbook/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

یک کتاب‌کار را نشان می‌دهد که دسترسی به داده‌های Excel را برای استفاده عمومی فراهم می‌کند.

## سازندگان

| سازنده | توضیح |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | یک نمونه جدید را با استفاده از مسیر فایل مشخص شده مقداردهی اولیه می‌کند. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | یک نمونه جدید از کلاس را با استفاده از جریان فراهم‌شده مقداردهی اولیه می‌کند. |

## متدها

| متد | توضیح |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | یک مجموعه‌ای از سلول‌ها را از کتاب‌کار که با فرمول مشخص شده مطابقت دارند، بازیابی می‌کند. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | یک سلول را از کاربرگ مشخص شده با استفاده از شاخص و مختصات سلول بازیابی می‌کند. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | یک سلول را از کاربرگ مشخص شده با استفاده از نام و مختصات سلول بازیابی می‌کند. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | یک سلول را از کاربرگ مشخص شده با استفاده از شاخص و نام سلول به سبک Excel (مثلاً "B2") بازیابی می‌کند. |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | یک سلول را از کاربرگ مشخص شده با استفاده از نام سلول به سبک Excel (مثلاً "B2") بازیابی می‌کند. |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | یک دیکشنری حاوی شاخص‌ها و نام‌های تمام نمودارها در کاربرگ مشخص شده یک کتاب‌کار Excel را بازیابی می‌کند. |
| [getWorksheetNames()](#getWorksheetNames--) | نام‌های تمام کاربرگ‌های موجود در کتاب‌کار Excel را بازیابی می‌کند. |

### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```

یک نمونه جدید را با استفاده از مسیر فایل مشخص شده مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filePath | java.lang.String | مسیر کامل به پرونده کتاب‌کار Excel. |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```

یک نمونه جدید از کلاس را با استفاده از جریان فراهم‌شده مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | یک جریان حاوی داده‌های کتاب‌کار Excel. |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

یک مجموعه‌ای از سلول‌ها را از کتاب‌کار که با فرمول مشخص شده مطابقت دارند، بازیابی می‌کند.

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Output: 5
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| formula | java.lang.String | یک فرمول یا عبارت بازه (مثلاً "Sheet1!A1:B3") که برای شناسایی سلول‌های هدف استفاده می‌شود. |
| skipHiddenCells | boolean | اگر true باشد، سلول‌های پنهان (مثلاً در سطرها یا ستون‌های مخفی) از نتایج حذف خواهند شد. |

**بازگشت:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - یک لیست فقط-خواندنی از سلول‌هایی که با فرمول مشخص شده مطابقت دارند.

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

یک سلول را از کاربرگ مشخص شده با استفاده از شاخص و مختصات سلول بازیابی می‌کند.

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
| worksheetIndex | int | شاخص صفر-پایه کاربرگ. |
| row | int | شاخص صفر-پایه سطر سلول. |
| column | int | شاخص صفر-پایه ستون سلول. |

**بازگشت:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - سلول در مکان مشخص شده.

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```

یک سلول را از کاربرگ مشخص شده با استفاده از نام و مختصات سلول بازیابی می‌کند.

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
| row | int | شاخص صفر-پایه سطر سلول. |
| column | int | شاخص صفر-پایه ستون سلول. |

**بازگشت:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - سلول در مکان مشخص شده.

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```

یک سلول را از کاربرگ مشخص شده با استفاده از شاخص و نام سلول به سبک Excel (مثلاً "B2") بازیابی می‌کند.

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
| worksheetIndex | int | شاخص صفر-پایه کاربرگ. |
| cellName | java.lang.String | مرجع سلول به سبک Excel (مثلاً "A1"، "C5"). |

**بازگشت:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - سلول در مکان مشخص شده.

### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```

یک سلول را از کاربرگ مشخص شده با استفاده از نام سلول به سبک Excel (مثلاً "B2") بازیابی می‌کند.

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
| cellName | java.lang.String | مرجع سلول به سبک Excel (مثلاً "A1"، "C5"). |

**بازگشت:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - سلول در مکان مشخص شده.

### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

یک دیکشنری حاوی شاخص‌ها و نام‌های تمام نمودارها در کاربرگ مشخص شده یک کتاب‌کار Excel را بازیابی می‌کند.

--------------------

> ```
> مثال:
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
| worksheetName | java.lang.String | نام کاربرگی که به دنبال نمودارها در آن می‌گردید. |

**بازگشت:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - یک دیکشنری که کلید آن شاخص نمودار و مقدار آن نام نمودار است.

### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
```

نام‌های تمام کاربرگ‌های موجود در کتاب‌کار Excel را بازیابی می‌کند.

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
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - یک لیست از نام‌های کاربرگ.