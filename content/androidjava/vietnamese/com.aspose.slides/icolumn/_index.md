---
title: IColumn
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một cột trong bảng.
type: docs
url: /vi/com.aspose.slides/icolumn/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

Biểu diễn một cột trong bảng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getWidth()](#getWidth--) | Trả về hoặc thiết lập độ rộng của một cột. |
| [setWidth(double value)](#setWidth-double-) | Trả về hoặc thiết lập độ rộng của một cột. |
| [getColumnFormat()](#getColumnFormat--) | Trả về đối tượng ColumnFormat chứa các thuộc tính định dạng cho cột này. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Trả về hoặc thiết lập độ rộng của một cột. Đọc/ghi double.

**Trả về:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Trả về hoặc thiết lập độ rộng của một cột. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

Trả về đối tượng ColumnFormat chứa các thuộc tính định dạng cho cột này. Chỉ đọc [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Trả về:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)