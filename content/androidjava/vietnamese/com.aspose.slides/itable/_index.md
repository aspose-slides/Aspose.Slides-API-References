---
title: ITable
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một bảng trên slide.
type: docs
url: /vi/com.aspose.slides/itable/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Biểu diễn một bảng trên slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Trả về ô tại các chỉ mục cột và hàng đã chỉ định. |
| [getRows()](#getRows--) | Trả về tập hợp các hàng. |
| [getColumns()](#getColumns--) | Trả về tập hợp các cột. |
| [getTableFormat()](#getTableFormat--) | Trả về đối tượng TableFormat chứa các thuộc tính định dạng cho bảng này. |
| [getStylePreset()](#getStylePreset--) | Lấy hoặc đặt kiểu bảng được tích hợp. |
| [setStylePreset(int value)](#setStylePreset-int-) | Lấy hoặc đặt kiểu bảng được tích hợp. |
| [getRightToLeft()](#getRightToLeft--) | Xác định liệu bảng có thứ tự đọc từ phải sang trái hay không. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Xác định liệu bảng có thứ tự đọc từ phải sang trái hay không. |
| [getFirstRow()](#getFirstRow--) | Xác định liệu hàng đầu tiên của bảng có cần được vẽ với định dạng đặc biệt hay không. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Xác định liệu hàng đầu tiên của bảng có cần được vẽ với định dạng đặc biệt hay không. |
| [getFirstCol()](#getFirstCol--) | Xác định liệu cột đầu tiên của bảng có cần được vẽ với định dạng đặc biệt hay không. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Xác định liệu cột đầu tiên của bảng có cần được vẽ với định dạng đặc biệt hay không. |
| [getLastRow()](#getLastRow--) | Xác định liệu hàng cuối cùng của bảng có cần được vẽ với định dạng đặc biệt hay không. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Xác định liệu hàng cuối cùng của bảng có cần được vẽ với định dạng đặc biệt hay không. |
| [getLastCol()](#getLastCol--) | Xác định liệu cột cuối cùng của bảng có cần được vẽ với định dạng đặc biệt hay không. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Xác định liệu cột cuối cùng của bảng có cần được vẽ với định dạng đặc biệt hay không. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Xác định liệu các hàng chẵn có cần được vẽ với định dạng khác hay không. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Xác định liệu các hàng chẵn có cần được vẽ với định dạng khác hay không. |
| [getVerticalBanding()](#getVerticalBanding--) | Xác định liệu các cột chẵn có cần được vẽ với định dạng khác hay không. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Xác định liệu các cột chẵn có cần được vẽ với định dạng khác hay không. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Hợp nhất các ô lân cận. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

Trả về ô tại các chỉ mục cột và hàng đã chỉ định. Chỉ đọc [ICell](../../com.aspose.slides/icell).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Trả về:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

Trả về tập hợp các hàng. Chỉ đọc [IRowCollection](../../com.aspose.slides/irowcollection).

**Trả về:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

Trả về tập hợp các cột. Chỉ đọc [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Trả về:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

Trả về đối tượng TableFormat chứa các thuộc tính định dạng cho bảng này. Chỉ đọc [ITableFormat](../../com.aspose.slides/itableformat).

**Trả về:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

Lấy hoặc đặt kiểu bảng được tích hợp. Đọc/ghi [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Trả về:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

Lấy hoặc đặt kiểu bảng được tích hợp. Đọc/ghi [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Xác định liệu bảng có thứ tự đọc từ phải sang trái hay không. Boolean đọc/ghi.

**Trả về:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

Xác định liệu bảng có thứ tự đọc từ phải sang trái hay không. Boolean đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

Xác định liệu hàng đầu tiên của bảng có cần được vẽ với định dạng đặc biệt hay không. Boolean đọc/ghi.

**Trả về:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

Xác định liệu hàng đầu tiên của bảng có cần được vẽ với định dạng đặc biệt hay không. Boolean đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

Xác định liệu cột đầu tiên của bảng có cần được vẽ với định dạng đặc biệt hay không. Boolean đọc/ghi.

**Trả về:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

Xác định liệu cột đầu tiên của bảng có cần được vẽ với định dạng đặc biệt hay không. Boolean đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

Xác định liệu hàng cuối cùng của bảng có cần được vẽ với định dạng đặc biệt hay không. Boolean đọc/ghi.

**Trả về:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

Xác định liệu hàng cuối cùng của bảng có cần được vẽ với định dạng đặc biệt hay không. Boolean đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

Xác định liệu cột cuối cùng của bảng có cần được vẽ với định dạng đặc biệt hay không. Boolean đọc/ghi.

**Trả về:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

Xác định liệu cột cuối cùng của bảng có cần được vẽ với định dạng đặc biệt hay không. Boolean đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

Xác định liệu các hàng chẵn có cần được vẽ với định dạng khác hay không. Boolean đọc/ghi.

**Trả về:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

Xác định liệu các hàng chẵn có cần được vẽ với định dạng khác hay không. Boolean đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

Xác định liệu các cột chẵn có cần được vẽ với định dạng khác hay không. Boolean đọc/ghi.

**Trả về:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

Xác định liệu các cột chẵn có cần được vẽ với định dạng khác hay không. Boolean đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Hợp nhất các ô lân cận.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Ô để hợp nhất. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Ô để hợp nhất. |
| allowSplitting | boolean | True để cho phép chia tách ô. |

**Trả về:**
[ICell](../../com.aspose.slides/icell) - Ô đã hợp nhất.