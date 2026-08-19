---
title: ExcelDataCell
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر یک سلول منفرد در یک کتاب‌کار Excel.
type: docs
url: /fa/com.aspose.slides/exceldatacell/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

نمایانگر یک سلول منفرد در یک کتاب‌کار Excel.

## متدها

| متد | توضیح |
| --- | --- |
| [getValue()](#getValue--) | مقدار موجود در سلول Excel را بازمی‌گرداند. |
| [getName()](#getName--) | نام سلول داده‌های نمودار را بازمی‌گرداند. |
| [getRow()](#getRow--) | اندیس صفرمحور ردیفی که سلول در آن واقع شده است را بازمی‌گرداند. |
| [getColumn()](#getColumn--) | اندیس صفرمحور ستونی که سلول در آن واقع شده است را بازمی‌گرداند. |
### getValue() {#getValue--}
```
public final Object getValue()
```

مقدار موجود در سلول Excel را بازمی‌گرداند.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**بازگشت:**
java.lang.Object
### getName() {#getName--}
```
public final String getName()
```

نام سلول داده‌های نمودار را بازمی‌گرداند.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //خروجی: "B2"
> ```


**بازگشت:**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
```

اندیس صفرمحور ردیفی که سلول در آن واقع شده است را بازمی‌گرداند. فقط-خواندنی int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //خروجی: 1
> ```


**بازگشت:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```

اندیس صفرمحور ستونی که سلول در آن واقع شده است را بازمی‌گرداند. فقط-خواندنی int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //خروجی: 1
> ```


**بازگشت:**
int