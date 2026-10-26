---
title: ExcelDataCell
second_title: Aspose.Slides Java API 参考
description: 表示 Excel 工作簿中的单个单元格。
type: docs
url: /zh/com.aspose.slides/exceldatacell/
---
**继承：**
java.lang.Object

**已实现的接口：**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
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

**返回：**
java.lang.Object
### getName() {#getName--}
```
public final String getName()
```

获取图表数据单元格的名称。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //输出: "B2"
> ```

**返回：**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
```

获取单元格所在工作表中行的零基索引。只读 int。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //输出: 1
> ```

**返回：**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```

获取单元格所在工作表中列的零基索引。只读 int。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //输出: 1
> ```

**返回：**
int