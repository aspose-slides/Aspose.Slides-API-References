---
title: IExcelDataCell
second_title: Aspose.Slides for Java API Reference
description: Represents a single cell in an Excel workbook.
type: docs
url: /com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Represents a single cell in an Excel workbook.
## Methods

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | Gets the value contained in the Excel cell. |
| [getName()](#getName--) | Gets the name of the chart data cell. |
| [getRow()](#getRow--) | Gets the zero-based index of the row in the worksheet where the cell is located. |
| [getColumn()](#getColumn--) | Gets the zero-based index of the column in the worksheet where the cell is located. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Gets the value contained in the Excel cell. Read-only  Object .

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Returns:**
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```


Gets the name of the chart data cell. Read-only String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Output: "B2"
> ```

**Returns:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```


Gets the zero-based index of the row in the worksheet where the cell is located. Read-only int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Output: 1
> ```

**Returns:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


Gets the zero-based index of the column in the worksheet where the cell is located. Read-only int.

--------------------

> ```
> Example:
>  
> v
> ```

**Returns:**
int
