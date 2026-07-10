---
title: ExcelDataCell
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示 Excel 工作簿中的单个单元格。
type: docs
url: /zh/com.aspose.slides/exceldatacell/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

表示 Excel 工作簿中的单元格。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getValue()](#getValue--) | 获取 Excel 单元格中包含的值。 |
| [getName()](#getName--) | 获取图表数据单元格的名称。 |
| [getRow()](#getRow--) | 获取单元格所在工作表中行的零基索引。 |
| [getColumn()](#getColumn--) | 获取单元格所在工作表中列的零基索引。 |
### getValue() {#getValue--}
```
public final Object getValue()
```


获取 Excel 单元格中包含的值。

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
>  System.out.println(cell.getName()); //输出: "B2"
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
>  System.out.println(cell.getRow()); //输出: 1
> ```

**Returns:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()


Gets the zero-based index of the column in the worksheet where the cell is located. Read-only int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Output: 1
> ```

**返回：**
int