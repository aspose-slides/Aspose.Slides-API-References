---
title: ExcelDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a single cell in an Excel workbook.
type: docs
url: /com.aspose.slides/exceldatacell/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
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
public final Object getValue()
```


Gets the value contained in the Excel cell.

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
public final String getName()
```


Gets the name of the chart data cell.

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
public final int getRow()
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
public final int getColumn()
```


Gets the zero-based index of the column in the worksheet where the cell is located. Read-only int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Output: 1
> ```

**Returns:**
int
