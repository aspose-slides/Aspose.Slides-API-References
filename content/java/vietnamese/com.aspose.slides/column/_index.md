---
title: Column
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một cột trong bảng.
type: docs
url: /vi/com.aspose.slides/column/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

Biểu diễn một cột trong bảng.
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getWidth()](#getWidth--) | Trả về hoặc đặt chiều rộng của cột. |
| [setWidth(double value)](#setWidth-double-) | Trả về hoặc đặt chiều rộng của cột. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Đặt các thuộc tính định dạng phần đã xác định cho tất cả các phần của ô cột. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Đặt các thuộc tính định dạng đoạn đã xác định cho tất cả các đoạn của ô cột. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Đặt các thuộc tính định dạng khung văn bản đã xác định cho tất cả các khung văn bản của ô cột. |
| [getColumnFormat()](#getColumnFormat--) | Trả về đối tượng ColumnFormat chứa các thuộc tính định dạng cho cột này. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Trả về hoặc đặt chiều rộng của cột. Đọc/ghi double.

**Trả về:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Trả về hoặc đặt chiều rộng của cột. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Đặt các thuộc tính định dạng phần đã xác định cho tất cả các phần của ô cột.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | đối tượng IPortionFormat với các thuộc tính cần thiết đã được thiết lập. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Đặt các thuộc tính định dạng đoạn đã xác định cho tất cả các đoạn của ô cột.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | đối tượng IParagraphFormat với các thuộc tính cần thiết đã được thiết lập. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Đặt các thuộc tính định dạng khung văn bản đã xác định cho tất cả các khung văn bản của ô cột.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | đối tượng ITextFrameFormat với các thuộc tính cần thiết đã được thiết lập. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```

Trả về đối tượng ColumnFormat chứa các thuộc tính định dạng cho cột này. Chỉ-đọc [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Trả về:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)