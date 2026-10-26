---
title: ICell
second_title: Tham chiếu API Java cho Aspose.Slides cho Android
description: Đại diện cho một ô trong bảng.
type: docs
url: /vi/com.aspose.slides/icell/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

Đại diện cho một ô trong bảng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Trả về khoảng cách từ phía bên trái của bảng đến phía bên trái của ô. |
| [getOffsetY()](#getOffsetY--) | Trả về khoảng cách từ phía trên của bảng đến phía trên của ô. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Trả về chỉ mục của hàng đầu tiên mà ô bao phủ. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Trả về chỉ mục của cột đầu tiên mà ô bao phủ. |
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
| [getFirstColumn()](#getFirstColumn--) | Lấy cột đầu tiên của ô. |
| [getFirstRow()](#getFirstRow--) | Lấy hàng đầu tiên của ô. |
| [getColSpan()](#getColSpan--) | Trả về số cột lưới trong lưới bảng của bảng cha mà ô hiện tại sẽ chiếm. |
| [getRowSpan()](#getRowSpan--) | Trả về số hàng mà một ô được hợp nhất chiếm. |
| [getTextFrame()](#getTextFrame--) | Trả về khung văn bản của ô. |
| [getTable()](#getTable--) | Trả về đối tượng Table cha cho ô. |
| [isMergedCell()](#isMergedCell--) | Trả về đúng nếu ô được hợp nhất với bất kỳ ô nào đã điều chỉnh, ngược lại trả về sai. |
| [getCellFormat()](#getCellFormat--) | Trả về đối tượng CellFormat chứa các thuộc tính định dạng cho ô này. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Tách ô thành hai ô theo chỉ mục của cột. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Tách ô thành hai ô theo chỉ mục của hàng. |
| [splitByHeight(double height)](#splitByHeight-double-) | Tách ô theo chiều cao. |
| [splitByWidth(double width)](#splitByWidth-double-) | Tách ô theo chiều rộng. |

### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

Trả về khoảng cách từ phía bên trái của bảng đến phía bên trái của ô. Chỉ đọc double.

**Trả về:**
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

Trả về khoảng cách từ phía trên của bảng đến phía trên của ô. Chỉ đọc double.

**Trả về:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```

Trả về chỉ mục của hàng đầu tiên mà ô bao phủ. Chỉ đọc int.

**Trả về:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```

Trả về chỉ mục của cột đầu tiên mà ô bao phủ. Chỉ đọc int.

**Trả về:**
int
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Trả về chiều rộng của ô. Chỉ đọc double.

**Trả về:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Trả về chiều cao của ô. Chỉ đọc double.

**Trả về:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Trả về chiều cao tối thiểu của ô. Đây là tổng chiều cao tối thiểu của tất cả các hàng mà ô bao phủ. Chỉ đọc double.

**Trả về:**
double
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Trả về hoặc đặt lề trái trong TextFrame. Đọc/ghi double.

**Trả về:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Trả về hoặc đặt lề trái trong TextFrame. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Trả về hoặc đặt lề phải trong TextFrame. Đọc/ghi double.

**Trả về:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Trả về hoặc đặt lề phải trong TextFrame. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Trả về hoặc đặt lề trên trong TextFrame. Đọc/ghi double.

**Trả về:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Trả về hoặc đặt lề trên trong TextFrame. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Trả về hoặc đặt lề dưới trong TextFrame. Đọc/ghi double.

**Trả về:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Trả về hoặc đặt lề dưới trong TextFrame. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Trả về hoặc đặt kiểu văn bản dọc. Đọc/ghi [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Trả về:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Trả về hoặc đặt kiểu văn bản dọc. Đọc/ghi [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

Trả về hoặc đặt kiểu neo văn bản. Đọc/ghi [TextAnchorType](../../com.aspose.slides/textanchortype).

**Trả về:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

Trả về hoặc đặt kiểu neo văn bản. Đọc/ghi [TextAnchorType](../../com.aspose.slides/textanchortype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

Xác định xem hộp văn bản có được căn giữa trong ô hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

Xác định xem hộp văn bản có được căn giữa trong ô hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```

Lấy cột đầu tiên của ô. Chỉ đọc [IColumn](../../com.aspose.slides/icolumn).

**Trả về:**
[IColumn](../../com.aspose.slides/icolumn)
### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```

Lấy hàng đầu tiên của ô. Chỉ đọc [IRow](../../com.aspose.slides/irow).

**Trả về:**
[IRow](../../com.aspose.slides/irow)
### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```

Trả về số cột lưới trong lưới bảng của bảng cha mà ô hiện tại sẽ chiếm. Thuộc tính này cho phép các ô có giao diện như đã được hợp nhất, vì chúng mở rộng qua ranh giới dọc của các ô khác trong bảng. Chỉ đọc int.

**Trả về:**
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

Trả về số hàng mà một ô được hợp nhất chiếm. Thuộc tính này được sử dụng cùng với thuộc tính vMerge trên các ô khác để xác định ô bắt đầu của một hợp nhất ngang. Chỉ đọc int.

**Trả về:**
int
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Trả về khung văn bản của ô. Chỉ đọc [ITextFrame](../../com.aspose.slides/itextframe).

**Trả về:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public abstract ITable getTable()
```

Trả về đối tượng Table cha cho ô. Chỉ đọc [ITable](../../com.aspose.slides/itable).

**Trả về:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

Trả về đúng nếu ô được hợp nhất với bất kỳ ô nào đã điều chỉnh, ngược lại trả về sai. Chỉ đọc boolean.

**Trả về:**
boolean
### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```

Trả về đối tượng CellFormat chứa các thuộc tính định dạng cho ô này. Chỉ đọc [ICellFormat](../../com.aspose.slides/icellformat).

**Trả về:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```

Tách ô thành hai ô theo chỉ mục của cột.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của cột. |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

Tách ô thành hai ô theo chỉ mục của hàng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của hàng. |

### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

Tách ô theo chiều cao.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| height | double | Chiều cao của một hàng. |

### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

Tách ô theo chiều rộng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| width | double | Chiều rộng của một cột. |