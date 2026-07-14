---
title: IExcelDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: یک سلول واحد در یک کتاب کار اکسل را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/iexceldatacell/
---
```
public interface IExcelDataCell
```

یک سلول واحد در یک کتاب کار اکسل را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getValue()](#getValue--) | مقدار موجود در سلول اکسل را دریافت می‌کند. |
| [getName()](#getName--) | نام سلول دادهٔ نمودار را دریافت می‌کند. |
| [getRow()](#getRow--) | نمایهٔ مبتنی بر صفر ردیف در برگه کاری که سلول در آن قرار دارد را دریافت می‌کند. |
| [getColumn()](#getColumn--) | نمایهٔ مبتنی بر صفر ستون در برگه کاری که سلول در آن قرار دارد را دریافت می‌کند. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

مقداری که در سلول اکسل موجود است را دریافت می‌کند. فقط-خواندنی Object .

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
public abstract String getName()
```

نام سلول دادهٔ نمودار را دریافت می‌کند. فقط-خواندنی String.

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
public abstract int getRow()
```

نمایهٔ مبتنی بر صفر ردیف در برگه کاری که سلول در آن قرار دارد را دریافت می‌کند. فقط-خواندنی int.

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
public abstract int getColumn()
```

نمایهٔ مبتنی بر صفر ستون در برگه کاری که سلول در آن قرار دارد را دریافت می‌کند. فقط-خواندنی int.

--------------------

> ```
> Example:
>  
> v
> ```

**بازگشت:**  
int