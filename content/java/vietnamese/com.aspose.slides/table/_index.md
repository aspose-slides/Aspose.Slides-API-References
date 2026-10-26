---
title: Table
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một bảng trên slide.
type: docs
url: /vi/com.aspose.slides/table/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

Biểu diễn một bảng trên slide.
## Phương thức

| Method | Description |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Trả về ô tại các chỉ mục cột và hàng đã chỉ định. |
| [getRows()](#getRows--) | Trả về tập hợp các hàng. |
| [getColumns()](#getColumns--) | Trả về tập hợp các cột. |
| [getTableFormat()](#getTableFormat--) | Trả về đối tượng TableFormat chứa các thuộc tính định dạng cho bảng này. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Hợp nhất các ô liền kề. |
| [getStylePreset()](#getStylePreset--) | Lấy hoặc đặt kiểu bảng tích hợp. |
| [setStylePreset(int value)](#setStylePreset-int-) | Lấy hoặc đặt kiểu bảng tích hợp. |
| [getRightToLeft()](#getRightToLeft--) | Xác định bảng có thứ tự đọc từ phải sang trái hay không. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Xác định bảng có thứ tự đọc từ phải sang trái hay không. |
| [getFirstRow()](#getFirstRow--) | Xác định xem hàng đầu tiên của bảng có phải được vẽ với định dạng đặc biệt hay không. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Xác định xem hàng đầu tiên của bảng có phải được vẽ với định dạng đặc biệt hay không. |
| [getFirstCol()](#getFirstCol--) | Xác định xem cột đầu tiên của bảng có phải được vẽ với định dạng đặc biệt hay không. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Xác định xem cột đầu tiên của bảng có phải được vẽ với định dạng đặc biệt hay không. |
| [getLastRow()](#getLastRow--) | Xác định xem hàng cuối cùng của bảng có phải được vẽ với định dạng đặc biệt hay không. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Xác định xem hàng cuối cùng của bảng có phải được vẽ với định dạng đặc biệt hay không. |
| [getLastCol()](#getLastCol--) | Xác định xem cột cuối cùng của bảng có phải được vẽ với định dạng đặc biệt hay không. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Xác định xem cột cuối cùng của bảng có phải được vẽ với định dạng đặc biệt hay không. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Xác định xem các hàng chẵn có phải được vẽ với định dạng khác nhau hay không. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Xác định xem các hàng chẵn có phải được vẽ với định dạng khác nhau hay không. |
| [getVerticalBanding()](#getVerticalBanding--) | Xác định xem các cột chẵn có phải được vẽ với định dạng khác nhau hay không. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Xác định xem các cột chẵn có phải được vẽ với định dạng khác nhau hay không. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Đặt các thuộc tính định dạng phần đã định nghĩa cho mọi phần của các ô bảng. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Đặt các thuộc tính định dạng đoạn đã định nghĩa cho các đoạn của mọi ô bảng. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Đặt các thuộc tính định dạng khung văn bản đã định nghĩa cho các khung văn bản của mọi ô bảng. |
| [getFillFormat()](#getFillFormat--) | Trả về đối tượng TableFormat.FillFormat chứa định dạng màu nền cho Bảng. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

Trả về ô tại các chỉ mục cột và hàng đã chỉ định. Chỉ đọc [Cell](../../com.aspose.slides/cell).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Trả về:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

Trả về tập hợp các hàng. Chỉ đọc [IRowCollection](../../com.aspose.slides/irowcollection).

**Trả về:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

Trả về tập hợp các cột. Chỉ đọc [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Trả về:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

Trả về đối tượng TableFormat chứa các thuộc tính định dạng cho bảng này. Chỉ đọc [ITableFormat](../../com.aspose.slides/itableformat).

**Trả về:**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Hợp nhất các ô liền kề.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Ô để hợp nhất. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Ô để hợp nhất. |
| allowSplitting | boolean | True để cho phép tách ô. |

**Trả về:**
[ICell](../../com.aspose.slides/icell) - Merged cell.

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

Lấy hoặc đặt kiểu bảng tích hợp. Đọc/ghi [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Trả về:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

Lấy hoặc đặt kiểu bảng tích hợp. Đọc/ghi [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

Xác định bảng có thứ tự đọc từ phải sang trái hay không. Đọc-ghi boolean .

**Trả về:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

Xác định bảng có thứ tự đọc từ phải sang trái hay không. Đọc-ghi boolean .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

Xác định xem hàng đầu tiên của bảng có phải được vẽ với định dạng đặc biệt hay không. Đọc/ghi boolean .

**Trả về:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

Xác định xem hàng đầu tiên của bảng có phải được vẽ với định dạng đặc biệt hay không. Đọc/ghi boolean .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

Xác định xem cột đầu tiên của bảng có phải được vẽ với định dạng đặc biệt hay không. Đọc/ghi boolean .

**Trả về:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

Xác định xem cột đầu tiên của bảng có phải được vẽ với định dạng đặc biệt hay không. Đọc/ghi boolean .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

Xác định xem hàng cuối cùng của bảng có phải được vẽ với định dạng đặc biệt hay không. Đọc/ghi boolean .

**Trả về:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

Xác định xem hàng cuối cùng của bảng có phải được vẽ với định dạng đặc biệt hay không. Đọc/ghi boolean .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

Xác định xem cột cuối cùng của bảng có phải được vẽ với định dạng đặc biệt hay không. Đọc/ghi boolean .

**Trả về:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

Xác định xem cột cuối cùng của bảng có phải được vẽ với định dạng đặc biệt hay không. Đọc/ghi boolean .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

Xác định xem các hàng chẵn có phải được vẽ với định dạng khác nhau hay không. Đọc/ghi boolean .

**Trả về:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

Xác định xem các hàng chẵn có phải được vẽ với định dạng khác nhau hay không. Đọc/ghi boolean .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

Xác định xem các cột chẵn có phải được vẽ với định dạng khác nhau hay không. Đọc/ghi boolean .

**Trả về:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

Xác định xem các cột chẵn có phải được vẽ với định dạng khác nhau hay không. Đọc/ghi boolean .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Đặt các thuộc tính định dạng phần đã định nghĩa cho mọi phần của các ô bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Đối tượng IPortionFormat với các thuộc tính cần thiết đã được đặt. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Đặt các thuộc tính định dạng đoạn đã định nghĩa cho các đoạn của mọi ô bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Đối tượng IParagraphFormat với các thuộc tính cần thiết đã được đặt. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Đặt các thuộc tính định dạng khung văn bản đã định nghĩa cho các khung văn bản của mọi ô bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Đối tượng ITextFrameFormat với các thuộc tính cần thiết đã được đặt. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Trả về đối tượng TableFormat.FillFormat chứa định dạng màu nền cho Bảng. Chỉ đọc [IFillFormat](../../com.aspose.slides/ifillformat).

**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)