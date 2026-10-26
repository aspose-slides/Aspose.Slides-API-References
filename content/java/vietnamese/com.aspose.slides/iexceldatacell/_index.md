---
title: IExcelDataCell
second_title: Aspose.Slides for Java API Reference
description: Đại diện cho một ô duy nhất trong một sổ làm việc Excel.
type: docs
url: /vi/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Đại diện cho một ô duy nhất trong một sổ làm việc Excel.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getValue()](#getValue--) | Lấy giá trị chứa trong ô Excel. |
| [getName()](#getName--) | Lấy tên của ô dữ liệu biểu đồ. |
| [getRow()](#getRow--) | Lấy chỉ số dựa trên số 0 của hàng trong bảng tính nơi ô được đặt. |
| [getColumn()](#getColumn--) | Lấy chỉ số dựa trên số 0 của cột trong bảng tính nơi ô được đặt. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Lấy giá trị chứa trong ô Excel. Chỉ đọc  Object .

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Trả về:**
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```


Lấy tên của ô dữ liệu biểu đồ. Chỉ đọc String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Kết quả: "B2"
> ```

**Trả về:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```


Lấy chỉ số dựa trên số 0 của hàng trong bảng tính nơi ô được đặt. Chỉ đọc int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Kết quả: 1
> ```

**Trả về:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


Lấy chỉ số dựa trên số 0 của cột trong bảng tính nơi ô được đặt. Chỉ đọc int.

--------------------

> ```
> Example:
>  
> v
> ```

**Trả về:**
int