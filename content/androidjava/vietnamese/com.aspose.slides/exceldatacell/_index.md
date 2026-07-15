---
title: ExcelDataCell
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn một ô đơn trong workbook Excel.
type: docs
url: /vi/com.aspose.slides/exceldatacell/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

Biểu diễn một ô đơn trong workbook Excel.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getValue()](#getValue--) | Lấy giá trị chứa trong ô Excel. |
| [getName()](#getName--) | Lấy tên của ô dữ liệu biểu đồ. |
| [getRow()](#getRow--) | Lấy chỉ mục dựa trên 0 của hàng trong worksheet nơi ô được đặt. |
| [getColumn()](#getColumn--) | Lấy chỉ mục dựa trên 0 của cột trong worksheet nơi ô được đặt. |
### getValue() {#getValue--}
```
public final Object getValue()
```


Lấy giá trị chứa trong ô Excel.

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
>  System.out.println(cell.getName()); //Kết quả: "B2"
> ```

**Trả về:**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
```


Lấy chỉ mục dựa trên 0 của hàng trong worksheet nơi ô được đặt. Chỉ-đọc int.

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
public final int getColumn()
```


Lấy chỉ mục dựa trên 0 của cột trong worksheet nơi ô được đặt. Chỉ-đọc int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Kết quả: 1
> ```

**Trả về:**
int