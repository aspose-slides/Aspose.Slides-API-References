---
title: ExcelDataWorkbook
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک کتاب‌کار را که دسترسی به داده‌های Excel را برای استفاده عمومی فراهم می‌کند نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/exceldataworkbook/
---
**وراثت:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)  
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

یک کتاب‌کار را نشان می‌دهد که دسترسی به داده‌های Excel را برای استفاده عمومی فراهم می‌کند.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | یک نمونه جدید را با استفاده از مسیر فایل مشخص‌شده مقداردهی اولیه می‌کند. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | یک نمونه جدید از کلاس را با استفاده از جریان ارائه‌شده مقداردهی اولیه می‌کند. |

## متدها

| متد | توضیح |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | یک مجموعه از سلول‌ها را از کتاب‌کار که با فرمول مشخص‌شده مطابقت دارند، بازیابی می‌کند. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | یک سلول را از برگه‌کار مشخص شده با استفاده از اندیس و مختصات سلول آن بازیابی می‌کند. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | یک سلول را از برگه‌کار مشخص شده با استفاده از نام و مختصات سلول آن بازیابی می‌کند. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | یک سلول را از برگه‌کار مشخص شده با استفاده از اندیس و نام سلول به سبک Excel (مثلاً "B2") بازیابی می‌کند. |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | یک سلول را از برگه‌کار مشخص شده با استفاده از نام سلول به سبک Excel (مثلاً "B2") بازیابی می‌کند. |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | یک دیکشنری شامل اندیس‌ها و نام‌های تمام نمودارها در برگه‌کار مشخص شده از یک کتاب‌کار Excel بازیابی می‌کند. |
| [getWorksheetNames()](#getWorksheetNames--) | نام‌های تمام برگه‌های موجود در کتاب‌کار Excel را بازیابی می‌کند. |

### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```

یک نمونه جدید را با استفاده از مسیر فایل مشخص‌شده مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filePath | java.lang.String | مسیر کامل فایل کتاب‌کار Excel. |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```

یک نمونه جدید از کلاس را با استفاده از جریان ارائه‌شده مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | یک جریان حاوی داده‌های کتاب‌کار Excel. |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

یک مجموعه از سلول‌ها را از کتاب‌کار که با فرمول مشخص‌شده مطابقت دارند، بازیابی می‌کند.

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //خروجی: 5
>  ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| formula | java.lang.String | یک فرمول یا عبارت بازه (مثلاً "Sheet1!A1:B3") که برای شناسایی سلول‌های هدف استفاده می‌شود. |
| skipHiddenCells | boolean | اگر true باشد، سلول‌های مخفی (مثلاً در ردیف‌ها یا ستون‌های مخفی) از نتیجه حذف می‌شوند. |

**بازگشت:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - یک لیست فقط-خواندنی از سلول‌هایی که با فرمول مشخص شده مطابقت دارند.

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

یک سلول را از برگه‌کار مشخص شده با استفاده از اندیس و مختصات سلول آن بازیابی می‌کند.

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
| worksheetIndex | int | اندیس صفر-مبنا از برگه‌کار. |
| row | int | اندیس صفر-مبنا از ردیف سلول. |
| column | int | اندیس صفر-مبنا از ستون سلول. |

**بازگشت:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - سلول در مکان مشخص‌شده.

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```

یک سلول را از برگه‌کار مشخص شده با استفاده از نام و مختصات سلول آن بازیابی می‌کند.

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
| worksheetName | java.lang.String | نام برگه‌کار. |
| row | int | اندیس صفر-مبنا از ردیف سلول. |
| column | int | اندیس صفر-مبنا از ستون سلول. |

**بازگشت:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - سلول در مکان مشخص‌شده.

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```

یک سلول را از برگه‌کار مشخص شده با استفاده از اندیس و نام سلول به سبک Excel (مثلاً "B2") بازیابی می‌کند.

--------------------

> ```
> مثال:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| worksheetIndex | int | اندیس صفر-مبنا از برگه‌کار. |
| cellName | java.lang.String | مرجع سلول به سبک Excel (مثلاً "A1"، "C5"). |

**بازگشت:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - سلول در مکان مشخص‌شده.

### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```

یک سلول را از برگه‌کار مشخص شده با استفاده از نام سلول به سبک Excel (مثلاً "B2") بازیابی می‌کند.

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
| worksheetName | java.lang.String | نام برگه‌کار. |
| cellName | java.lang.String | مرجع سلول به سبک Excel (مثلاً "A1"، "C5"). |

**بازگشت:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - سلول در مکان مشخص‌شده.

### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

یک دیکشنری شامل اندیس‌ها و نام‌های تمام نمودارها در برگه‌کار مشخص شده از یک کتاب‌کار Excel بازیابی می‌کند.

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
| worksheetName | java.lang.String | نام برگه‌کار برای جستجوی نمودارها. |

**بازگشت:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - یک دیکشنری که کلید آن اندیس نمودار و مقدار آن نام نمودار است.

### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
```

یک لیست از نام‌های برگه‌ها را بازیابی می‌کند.

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
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - یک لیست از نام‌های برگه‌ها