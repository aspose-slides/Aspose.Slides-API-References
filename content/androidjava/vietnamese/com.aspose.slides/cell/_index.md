---
title: Cell
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một ô của bảng.
type: docs
url: /vi/com.aspose.slides/cell/
---
**Kế thừa:**
java.lang.Object

**Tất cả giao diện được triển khai:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

Biểu diễn một ô của bảng.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Trả về khoảng cách từ phía bên trái của bảng tới phía bên trái của ô. |
| [getOffsetY()](#getOffsetY--) | Trả về khoảng cách từ phía trên của bảng tới phía trên của ô. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Trả về chỉ số của hàng đầu tiên mà ô bao phủ. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Trả về chỉ số của cột đầu tiên mà ô bao phủ. |
| [getWidth()](#getWidth--) | Trả về chiều rộng của ô. |
| [getHeight()](#getHeight--) | Trả về chiều cao của ô. |
| [getMinimalHeight()](#getMinimalHeight--) | Trả về chiều cao tối thiểu của ô. |
| [getMarginLeft()](#getMarginLeft--) | Trả về hoặc đặt lề trái trong TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Trả về hoặc đặt lề trái trong TextFrame. |
| [getMarginRight()](#getMarginRight--) | Trả về hoặc đặt lề phải trong TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Trả về hoặc đặt lề phải trong TextFrame. |
| [getMarginTop()](#getMarginTop--) | Trả về hoặc đặt lề trên trong TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Trả về hoặc đặt lề trên trong TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Trả về hoặc đặt lề dưới trong TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Trả về hoặc đặt lề dưới trong TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | Trả về hoặc đặt kiểu văn bản dọc. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Trả về hoặc đặt kiểu văn bản dọc. |
| [getTextAnchorType()](#getTextAnchorType--) | Trả về hoặc đặt kiểu neo văn bản. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Trả về hoặc đặt kiểu neo văn bản. |
| [getAnchorCenter()](#getAnchorCenter--) | Xác định xem hộp văn bản có được căn giữa trong ô hay không. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Xác định xem hộp văn bản có được căn giữa trong ô hay không. |
| [getFirstRow()](#getFirstRow--) | Lấy hàng đầu tiên của ô. |
| [getFirstColumn()](#getFirstColumn--) | Lấy cột đầu tiên của ô. |
| [getColSpan()](#getColSpan--) | Trả về số cột lưới trong lưới bảng của bảng cha sẽ được ô hiện tại chiếm. |
| [getRowSpan()](#getRowSpan--) | Trả về số hàng mà ô hợp nhất chiếm. |
| [getTextFrame()](#getTextFrame--) | Trả về khung văn bản của ô. |
| [getTable()](#getTable--) | Trả về đối tượng Table cha của ô. |
| [isMergedCell()](#isMergedCell--) | Trả về true nếu ô được hợp nhất với bất kỳ ô nào được điều chỉnh, ngược lại trả về false. |
| [getCellFormat()](#getCellFormat--) | Trả về đối tượng CellFormat chứa các thuộc tính định dạng cho ô này. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Chia ô thành hai ô theo chỉ số cột. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Chia ô thành hai ô theo chỉ số hàng. |
| [splitByHeight(double height)](#splitByHeight-double-) | Chia ô theo chiều cao. |
| [splitByWidth(double width)](#splitByWidth-double-) | Chia ô theo chiều rộng. |
| [getSlide()](#getSlide--) | Trả về slide cha của ô. |
| [getPresentation()](#getPresentation--) | Trả về bản trình bày cha của ô. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

Trả về khoảng cách từ phía bên trái của bảng tới phía bên trái của ô. Chỉ đọc double.

**Returns:**
double
### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

Trả về khoảng cách từ phía trên của bảng tới phía trên của ô. Chỉ đọc double.

**Returns:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

Trả về chỉ số của hàng đầu tiên mà ô bao phủ. Chỉ đọc int.

**Returns:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

Trả về chỉ số của cột đầu tiên mà ô bao phủ. Chỉ đọc int.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Trả về chiều rộng của ô. Chỉ đọc double.

**Returns:**
double
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Trả về chiều cao của ô. Chỉ đọc double.

**Returns:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Trả về chiều cao tối thiểu của ô. Đây là tổng chiều cao tối thiểu của tất cả các hàng mà ô bao phủ. Chỉ đọc double.

**Returns:**
double
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Trả về hoặc đặt lề trái trong TextFrame. Đọc/ghi double.

**Returns:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Trả về hoặc đặt lề trái trong TextFrame. Đọc/ghi double.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Trả về hoặc đặt lề phải trong TextFrame. Đọc/ghi double.

**Returns:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Trả về hoặc đặt lề phải trong TextFrame. Đọc/ghi double.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Trả về hoặc đặt lề trên trong TextFrame. Đọc/ghi double.

**Returns:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Trả về hoặc đặt lề trên trong TextFrame. Đọc/ghi double.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Trả về hoặc đặt lề dưới trong TextFrame. Đọc/ghi double.

**Returns:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Trả về hoặc đặt lề dưới trong TextFrame. Đọc/ghi double.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Trả về hoặc đặt kiểu văn bản dọc. Đọc/ghi [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Returns:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Trả về hoặc đặt kiểu văn bản dọc. Đọc/ghi [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

Trả về hoặc đặt kiểu neo văn bản. Đọc/ghi [TextAnchorType](../../com.aspose.slides/textanchortype).

**Returns:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

Trả về hoặc đặt kiểu neo văn bản. Đọc/ghi [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

Xác định xem hộp văn bản có được căn giữa trong ô hay không. Đọc/ghi boolean.

**Returns:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

Xác định xem hộp văn bản có được căn giữa trong ô hay không. Đọc/ghi boolean.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

Lấy hàng đầu tiên của ô. Chỉ đọc [IRow](../../com.aspose.slides/irow).

**Returns:**
[IRow](../../com.aspose.slides/irow)
### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

Lấy cột đầu tiên của ô. Chỉ đọc [IColumn](../../com.aspose.slides/icolumn).

**Returns:**
[IColumn](../../com.aspose.slides/icolumn)
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

Trả về số cột lưới trong lưới bảng của bảng cha sẽ được ô hiện tại chiếm. Thuộc tính này cho phép các ô có vẻ như được hợp nhất, vì chúng kéo dài qua ranh giới dọc của các ô khác trong bảng. Chỉ đọc int.

**Returns:**
int
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

Trả về số hàng mà ô hợp nhất chiếm. Thuộc tính này được sử dụng cùng với thuộc tính vMerge trên các ô khác để xác định ô bắt đầu của một phép hợp nhất ngang. Chỉ đọc int.

**Returns:**
int
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Trả về khung văn bản của ô. Chỉ đọc [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public final ITable getTable()
```

Trả về đối tượng Table cha của ô. Chỉ đọc [ITable](../../com.aspose.slides/itable).

**Returns:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

Trả về true nếu ô được hợp nhất với bất kỳ ô nào được điều chỉnh, false nếu không. Chỉ đọc boolean.

**Returns:**
boolean
### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

Trả về đối tượng CellFormat chứa các thuộc tính định dạng cho ô này. Chỉ đọc [ICellFormat](../../com.aspose.slides/icellformat).

**Returns:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

Chia ô thành hai ô theo chỉ số cột.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của cột. |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

Chia ô thành hai ô theo chỉ số hàng.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của hàng. |

### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

Chia ô theo chiều cao.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| height | double | Chiều cao của một hàng. |

### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

Chia ô theo chiều rộng.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| width | double | Chiều rộng của một cột. |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Trả về slide cha của ô. Chỉ đọc [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Trả về bản trình bày cha của ô. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject