---
title: IRow
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một hàng trong bảng.
type: docs
url: /vi/com.aspose.slides/irow/
---
**Tất cả các giao diện được thực thi:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

Biểu diễn một hàng trong bảng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getHeight()](#getHeight--) | Trả về chiều cao của một hàng. |
| [getMinimalHeight()](#getMinimalHeight--) | Trả về hoặc đặt chiều cao tối thiểu có thể của một hàng. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Trả về hoặc đặt chiều cao tối thiểu có thể của một hàng. |
| [getRowFormat()](#getRowFormat--) | Trả về đối tượng RowFormat chứa các thuộc tính định dạng cho hàng này. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Trả về chiều cao của một hàng. Chỉ-đọc double.

**Trả về:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


Trả về hoặc đặt chiều cao tối thiểu có thể của một hàng. Đọc/ghi double.

**Trả về:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```


Trả về hoặc đặt chiều cao tối thiểu có thể của một hàng. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```


Trả về đối tượng RowFormat chứa các thuộc tính định dạng cho hàng này. Chỉ-đọc [IRowFormat](../../com.aspose.slides/irowformat).

**Trả về:**
[IRowFormat](../../com.aspose.slides/irowformat)