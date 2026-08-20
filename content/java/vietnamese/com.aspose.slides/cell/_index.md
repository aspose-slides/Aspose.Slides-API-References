---
title: Cell
second_title: Tài liệu tham khảo API Aspose.Slides cho Java
description: Biểu diễn một ô của bảng.
type: docs
url: /vi/com.aspose.slides/cell/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

Biểu diễn một ô của bảng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Trả về khoảng cách từ phía trái của bảng tới phía trái của ô. |
| [getOffsetY()](#getOffsetY--) | Trả về khoảng cách từ phía trên của bảng tới phía trên của ô. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Trả về chỉ số của hàng đầu tiên mà ô bao phủ. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Trả về chỉ số của cột đầu tiên mà ô bao phủ. |
| [getWidth()](#getWidth--) | Trả về chiều rộng của ô. |
| [getHeight()](#getHeight--) | Trả về chiều cao của ô. |
| [getMinimalHeight()](#getMinimalHeight--) | Trả về chiều cao tối thiểu của ô. |
| [getMarginLeft()](#getMarginLeft--) | Trả về hoặc thiết lập lề trái trong TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Trả về hoặc thiết lập lề trái trong TextFrame. |
| [getMarginRight()](#getMarginRight--) | Trả về hoặc thiết lập lề phải trong TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Trả về hoặc thiết lập lề phải trong TextFrame. |
| [getMarginTop()](#getMarginTop--) | Trả về hoặc thiết lập lề trên trong TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Trả về hoặc thiết lập lề trên trong TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Trả về hoặc thiết lập lề dưới trong TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Trả về hoặc thiết lập lề dưới trong TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | Trả về hoặc thiết lập kiểu văn bản dọc. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Trả về hoặc thiết lập kiểu văn bản dọc. |
| [getTextAnchorType()](#getTextAnchorType--) | Trả về hoặc thiết lập kiểu neo văn bản. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Trả về hoặc thiết lập kiểu neo văn bản. |
| [getAnchorCenter()](#getAnchorCenter--) | Xác định xem hộp văn bản có được căn giữa trong ô hay không. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Xác định xem hộp văn bản có được căn giữa trong ô hay không. |
| [getFirstRow()](#getFirstRow--) | Lấy hàng đầu tiên của ô. |
| [getFirstColumn()](#getFirstColumn--) | Lấy cột đầu tiên của ô. |
| [getColSpan()](#getColSpan--) | Trả về số cột lưới trong lưới bảng cha mà ô hiện tại sẽ trải qua. |
| [getRowSpan()](#getRowSpan--) | Trả về số hàng mà một ô đã hợp nhất trải qua. |
| [getTextFrame()](#getTextFrame--) | Trả về khung văn bản của ô. |
| [getTable()](#getTable--) | Trả về đối tượng Table cha của ô. |
| [isMergedCell()](#isMergedCell--) | Trả về true nếu ô được hợp nhất với bất kỳ ô nào đã điều chỉnh, false nếu không. |
| [getCellFormat()](#getCellFormat--) | Trả về đối tượng CellFormat chứa các thuộc tính định dạng cho ô này. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Tách ô thành hai ô theo chỉ số cột. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Tách ô thành hai ô theo chỉ số hàng. |
| [splitByHeight(double height)](#splitByHeight-double-) | Tách ô theo chiều cao. |
| [splitByWidth(double width)](#splitByWidth-double-) | Tách ô theo chiều rộng. |
| [getSlide()](#getSlide--) | Trả về slide cha của ô. |
| [getPresentation()](#getPresentation--) | Trả về bản trình bày cha của ô. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

Trả về khoảng cách từ phía trái của bảng tới phía trái của ô. Chỉ đọc double.

**Trả về:**
double

### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

Trả về khoảng cách từ phía trên của bảng tới phía trên của ô. Chỉ đọc double.

**Trả về:**
double

### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

Trả về chỉ số của hàng đầu tiên mà ô bao phủ. Chỉ đọc int.

**Trả về:**
int

### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

Trả về chỉ số của cột đầu tiên mà ô bao phủ. Chỉ đọc int.

**Trả về:**
int

### getWidth() {#getWidth--}
```
public final double getWidth()
```

Trả về chiều rộng của ô. Chỉ đọc double.

**Trả về:**
double

### getHeight() {#getHeight--}
```
public final double getHeight()
```

Trả về chiều cao của ô. Chỉ đọc double.

**Trả về:**
double

### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Trả về chiều cao tối thiểu của ô. Đây là tổng chiều cao tối thiểu của tất cả các hàng mà ô bao phủ. Chỉ đọc double.

**Trả về:**
double

### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Trả về hoặc thiết lập lề trái trong TextFrame. Đọc/ghi double.

**Trả về:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Trả về hoặc thiết lập lề trái trong TextFrame. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Trả về hoặc thiết lập lề phải trong TextFrame. Đọc/ghi double.

**Trả về:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Trả về hoặc thiết lập lề phải trong TextFrame. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Trả về hoặc thiết lập lề trên trong TextFrame. Đọc/ghi double.

**Trả về:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Trả về hoặc thiết lập lề trên trong TextFrame. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Trả về hoặc thiết lập lề dưới trong TextFrame. Đọc/ghi double.

**Trả về:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Trả về hoặc thiết lập lề dưới trong TextFrame. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Trả về hoặc thiết lập kiểu văn bản dọc. Đọc/ghi [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Trả về:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Trả về hoặc thiết lập kiểu văn bản dọc. Đọc/ghi [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

Trả về hoặc thiết lập kiểu neo văn bản. Đọc/ghi [TextAnchorType](../../com.aspose.slides/textanchortype).

**Trả về:**
byte

### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

Trả về hoặc thiết lập kiểu neo văn bản. Đọc/ghi [TextAnchorType](../../com.aspose.slides/textanchortype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

Xác định xem hộp văn bản có được căn giữa trong ô hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

Xác định xem hộp văn bản có được căn giữa trong ô hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

Lấy hàng đầu tiên của ô. Chỉ đọc [IRow](../../com.aspose.slides/irow).

**Trả về:**
[IRow](../../com.aspose.slides/irow)

### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

Lấy cột đầu tiên của ô. Chỉ đọc [IColumn](../../com.aspose.slides/icolumn).

**Trả về:**
[IColumn](../../com.aspose.slides/icolumn)

### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

Trả về số cột lưới trong lưới bảng cha mà ô hiện tại sẽ trải qua. Thuộc tính này cho phép các ô có vẻ như được hợp nhất, vì chúng trải qua các ranh giới dọc của các ô khác trong bảng. Chỉ đọc int.

**Trả về:**
int

### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

Trả về số hàng mà một ô đã hợp nhất trải qua. Thuộc tính này được sử dụng cùng với thuộc tính vMerge trên các ô khác để chỉ định ô bắt đầu của một sự hợp nhất ngang. Chỉ đọc int.

**Trả về:**
int

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Trả về khung văn bản của ô. Chỉ đọc [ITextFrame](../../com.aspose.slides/itextframe).

**Trả về:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTable() {#getTable--}
```
public final ITable getTable()
```

Trả về đối tượng Table cha của ô. Chỉ đọc [ITable](../../com.aspose.slides/itable).

**Trả về:**
[ITable](../../com.aspose.slides/itable)

### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

Trả về true nếu ô được hợp nhất với bất kỳ ô nào đã điều chỉnh, false nếu không. Chỉ đọc boolean.

**Trả về:**
boolean

### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

Trả về đối tượng CellFormat chứa các thuộc tính định dạng cho ô này. Chỉ đọc [ICellFormat](../../com.aspose.slides/icellformat).

**Trả về:**
[ICellFormat](../../com.aspose.slides/icellformat)

### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

Tách ô thành hai ô theo chỉ số cột.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của cột. |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

Tách ô thành hai ô theo chỉ số hàng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của hàng. |

### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

Tách ô theo chiều cao.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| height | double | Chiều cao của một hàng. |

### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

Tách ô theo chiều rộng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| width | double | Chiều rộng của một cột. |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Trả về slide cha của ô. Chỉ đọc [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Trả về bản trình bày cha của ô. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject