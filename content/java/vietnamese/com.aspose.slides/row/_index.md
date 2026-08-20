---
title: Row
second_title: Tham chiếu API Aspose.Slides cho Java
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
| [getMinimalHeight()](#getMinimalHeight--) | Trả về hoặc thiết lập chiều cao tối thiểu có thể của một hàng. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Trả về hoặc thiết lập chiều cao tối thiểu có thể của một hàng. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Thiết lập các thuộc tính định dạng phần đã định nghĩa cho tất cả các phần của các ô trong hàng. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Thiết lập các thuộc tính định dạng đoạn văn đã định nghĩa cho tất cả các đoạn văn của các ô trong hàng. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Thiết lập các thuộc tính định dạng khung văn bản đã định nghĩa cho tất cả các khung văn bản của các ô trong hàng. |
| [getRowFormat()](#getRowFormat--) | Trả về đối tượng RowFormat chứa các thuộc tính định dạng cho hàng này. |
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Trả về chiều cao của một hàng. double chỉ đọc.

**Trả về:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Trả về hoặc thiết lập chiều cao tối thiểu có thể của một hàng. Đọc/ghi double.

**Trả về:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

Trả về hoặc thiết lập chiều cao tối thiểu có thể của một hàng. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Thiết lập các thuộc tính định dạng phần đã định nghĩa cho tất cả các phần của các ô trong hàng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Đối tượng IPortionFormat với các thuộc tính cần thiết đã được thiết lập. |
### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Thiết lập các thuộc tính định dạng đoạn văn đã định nghĩa cho tất cả các đoạn văn của các ô trong hàng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Đối tượng IParagraphFormat với các thuộc tính cần thiết đã được thiết lập. |
### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Thiết lập các thuộc tính định dạng khung văn bản đã định nghĩa cho tất cả các khung văn bản của các ô trong hàng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Đối tượng ITextFrameFormat với các thuộc tính cần thiết đã được thiết lập. |
### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

Trả về đối tượng RowFormat chứa các thuộc tính định dạng cho hàng này. [IRowFormat](../../com.aspose.slides/irowformat) chỉ đọc.

**Trả về:**
[IRowFormat](../../com.aspose.slides/irowformat)