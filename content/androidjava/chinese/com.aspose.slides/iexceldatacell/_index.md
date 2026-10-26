---
title: IExcelDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: 表示 Excel 工作簿中的单个单元格。
type: docs
url: /zh/com.aspose.slides/iexceldatacell/
---``` 
public interface IExcelDataCell
```

表示 Excel 工作簿中的单个单元格。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getValue()](#getValue--) | 获取 Excel 单元格中包含的值。 |
| [getName()](#getName--) | 获取图表数据单元格的名称。 |
| [getRow()](#getRow--) | 获取单元格所在工作表中行的零基索引。 |
| [getColumn()](#getColumn--) | 获取单元格所在工作表中列的零基索引。 |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

获取 Excel 单元格中包含的值。只读 Object .

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
>  System.out.println(cell.getName()); //输出: "B2"
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
>  System.out.println(cell.getRow()); //输出: 1
> ```

**Returns:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()

获取单元格所在工作表中列的零基索引。只读 int.

--------------------

> ```
> Example:
>  
> v
> ```

**返回值：**
int