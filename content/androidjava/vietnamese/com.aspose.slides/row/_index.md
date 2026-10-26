---
title: Row
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một hàng trong bảng.
type: docs
url: /vi/com.aspose.slides/row/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

Biểu diễn một hàng trong bảng.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getHeight()](#getHeight--) | Trả về chiều cao của một hàng. |
| [getMinimalHeight()](#getMinimalHeight--) | Trả về hoặc đặt chiều cao tối thiểu có thể của một hàng. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Trả về hoặc đặt chiều cao tối thiểu có thể của một hàng. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Đặt các thuộc tính định dạng phần đã xác định cho tất cả các phần của các ô hàng. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Đặt các thuộc tính định dạng đoạn văn đã xác định cho tất cả các đoạn văn của các ô hàng. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Đặt các thuộc tính định dạng khung văn bản đã xác định cho tất cả các khung văn bản của các ô hàng. |
| [getRowFormat()](#getRowFormat--) | Trả về đối tượng RowFormat chứa các thuộc tính định dạng cho hàng này. |

### getHeight() {#getHeight--}
```
public final double getHeight()
```

Trả về chiều cao của một hàng. **Chỉ đọc double.**

**Trả về:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Trả về hoặc đặt chiều cao tối thiểu có thể của một hàng. **Đọc/ghi double.**

**Trả về:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

Trả về hoặc đặt chiều cao tối thiểu có thể của một hàng. **Đọc/ghi double.**

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Đặt các thuộc tính định dạng phần đã xác định cho tất cả các phần của các ô hàng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat object with necessary properties set. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Đặt các thuộc tính định dạng đoạn văn đã xác định cho tất cả các đoạn văn của các ô hàng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat object with necessary properties set. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Đặt các thuộc tính định dạng khung văn bản đã xác định cho tất cả các khung văn bản của các ô hàng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat object with necessary properties set. |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

Trả về đối tượng RowFormat chứa các thuộc tính định dạng cho hàng này. **Chỉ đọc [IRowFormat](../../com.aspose.slides/irowformat).**

**Trả về:**
[IRowFormat](../../com.aspose.slides/irowformat)