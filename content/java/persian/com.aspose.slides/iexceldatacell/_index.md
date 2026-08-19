---
title: IExcelDataCell
second_title: Aspose.Slides for Java API Reference
description: یک سلول واحد در یک کتاب کار Excel را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

یک سلول واحد در یک کتاب کار Excel را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getValue()](#getValue--) | مقدار موجود در سلول Excel را دریافت می‌کند. |
| [getName()](#getName--) | نام سلول داده نمودار را دریافت می‌کند. |
| [getRow()](#getRow--) | شاخص صفر-پایه ردیف در برگه کاری که سلول در آن قرار دارد را دریافت می‌کند. |
| [getColumn()](#getColumn--) | شاخص صفر-پایه ستون در برگه کاری که سلول در آن قرار دارد را دریافت می‌کند. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

مقدار موجود در سلول Excel را دریافت می‌کند. فقط-خواندنی  Object .

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**باز می‌گرداند:**
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```

نام سلول داده نمودار را دریافت می‌کند. فقط-خواندنی String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //خروجی: "B2"
> ```

**باز می‌گرداند:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```

شاخص صفر-پایه ردیف در برگه کاری که سلول در آن قرار دارد را دریافت می‌کند. فقط-خواندنی int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //خروجی: 1
> ```


**باز می‌گرداند:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```

شاخص صفر-پایه ستون در برگه کاری که سلول در آن قرار دارد را دریافت می‌کند. فقط-خواندنی int.

--------------------

> ```
> Example:
>  
> v
> ```

**باز می‌گرداند:**
int