---
title: IExcelDataCell
second_title: Aspose.Slides for Java API Reference
description: Represents a single cell in an Excel workbook.
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


获取 Excel 单元格中包含的值。只读 Object 。

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
public abstract String getName()
```


获取图表数据单元格的名称。只读 String。

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
public abstract int getRow()
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
public abstract int getColumn()
```


获取单元格所在工作表中列的零基索引。只读 int。

--------------------

> ```
> Example:
>  
> v
> ```

**返回：**
int