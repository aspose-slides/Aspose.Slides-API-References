---
title: ExcelDataCell
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نماینده یک سلول منفرد در یک کتاب کار Excel است.
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

نماینده یک سلول منفرد در یک کتاب کار Excel است.
## متدها

| متد | توضیح |
| --- | --- |
| [getValue()](#getValue--) | مقدار موجود در سلول Excel را دریافت می‌کند. |
| [getName()](#getName--) | نام سلول داده نمودار را دریافت می‌کند. |
| [getRow()](#getRow--) | شاخص صفر-پایه ردیف در کاربرگی که سلول در آن قرار دارد را دریافت می‌کند. |
| [getColumn()](#getColumn--) | شاخص صفر-پایه ستون در کاربرگی که سلول در آن قرار دارد را دریافت می‌کند. |
### getValue() {#getValue--}
```
public final Object getValue()
```


مقدار موجود در سلول Excel را دریافت می‌کند.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**برگشت:**
java.lang.Object
### getName() {#getName--}
```
public final String getName()
```


نام سلول داده نمودار را دریافت می‌کند.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //خروجی: "B2"
> ```

**برگشت:**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
```


شاخص صفر-پایه ردیف در کاربرگی که سلول در آن قرار دارد را دریافت می‌کند. فقط-خواندنی int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //خروجی: 1
> ```

**برگشت:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```


شاخص صفر-پایه ستون در کاربرگی که سلول در آن قرار دارد را دریافت می‌کند. فقط-خواندنی int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //خروجی: 1
> ```

**برگشت:**
int