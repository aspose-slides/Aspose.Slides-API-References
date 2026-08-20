---
title: ExcelDataCell
second_title: Tham khảo API Aspose.Slides cho Java
description: Đại diện cho một ô đơn trong một sổ làm việc Excel.
type: docs
url: /vi/com.aspose.slides/exceldatacell/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

Đại diện cho một ô đơn trong một sổ làm việc Excel.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getValue()](#getValue--) | Lấy giá trị trong ô Excel. |
| [getName()](#getName--) | Lấy tên của ô dữ liệu biểu đồ. |
| [getRow()](#getRow--) | Lấy chỉ mục bắt đầu từ 0 của hàng trong trang tính nơi ô được đặt. |
| [getColumn()](#getColumn--) | Lấy chỉ mục bắt đầu từ 0 của cột trong trang tính nơi ô được đặt. |
### getValue() {#getValue--}
```
public final Object getValue()
```

Lấy giá trị trong ô Excel.

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
public final String getName()
```

Lấy tên của ô dữ liệu biểu đồ.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Đầu ra: "B2"
> ```


**Trả về:**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
```

Lấy chỉ mục bắt đầu từ 0 của hàng trong trang tính nơi ô được đặt. Chỉ đọc int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Đầu ra: 1
> ```


**Trả về:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```

Lấy chỉ mục bắt đầu từ 0 của cột trong trang tính nơi ô được đặt. Chỉ đọc int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Đầu ra: 1
> ```


**Trả về:**
int