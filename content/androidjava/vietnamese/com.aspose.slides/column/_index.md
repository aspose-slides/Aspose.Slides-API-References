---
title: Column
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một cột trong bảng.
type: docs
url: /vi/com.aspose.slides/column/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

Biểu diễn một cột trong bảng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getWidth()](#getWidth--) | Trả về hoặc thiết lập độ rộng của cột. |
| [setWidth(double value)](#setWidth-double-) | Trả về hoặc thiết lập độ rộng của cột. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Thiết lập các thuộc tính định dạng portion đã xác định cho tất cả các portion của các ô trong cột. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Thiết lập các thuộc tính định dạng paragraph đã xác định cho tất cả các paragraph của các ô trong cột. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Thiết lập các thuộc tính định dạng text frame đã xác định cho tất cả các text frame của các ô trong cột. |
| [getColumnFormat()](#getColumnFormat--) | Trả về đối tượng ColumnFormat chứa các thuộc tính định dạng cho cột này. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Trả về hoặc thiết lập độ rộng của cột. Đọc/ghi double.

**Trả về:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Trả về hoặc thiết lập độ rộng của cột. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Thiết lập các thuộc tính định dạng portion đã xác định cho tất cả các portion của các ô trong cột.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Đối tượng IPortionFormat với các thuộc tính cần thiết đã được thiết lập. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Thiết lập các thuộc tính định dạng paragraph đã xác định cho tất cả các paragraph của các ô trong cột.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Đối tượng IParagraphFormat với các thuộc tính cần thiết đã được thiết lập. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFrameFormat(ITextFrameFormat source)
```

Thiết lập các thuộc tính định dạng text frame đã xác định cho tất cả các text frame của các ô trong cột.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Đối tượng ITextFrameFormat với các thuộc tính cần thiết đã được thiết lập. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```

Trả về đối tượng ColumnFormat chứa các thuộc tính định dạng cho cột này. Chỉ đọc [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Trả về:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)