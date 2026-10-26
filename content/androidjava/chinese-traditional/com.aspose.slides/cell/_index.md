---
title: Cell
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示表格中的儲存格。
type: docs
url: /zh-hant/com.aspose.slides/cell/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

表示表格中的一個儲存格。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | 傳回表格左側到儲存格左側的距離。 |
| [getOffsetY()](#getOffsetY--) | 傳回表格上側到儲存格上側的距離。 |
| [getFirstRowIndex()](#getFirstRowIndex--) | 傳回儲存格所覆蓋的第一列索引。 |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | 傳回儲存格所覆蓋的第一欄索引。 |
| [getWidth()](#getWidth--) | 傳回儲存格的寬度。 |
| [getHeight()](#getHeight--) | 傳回儲存格的高度。 |
| [getMinimalHeight()](#getMinimalHeight--) | 傳回儲存格的最小高度。 |
| [getMarginLeft()](#getMarginLeft--) | 傳回或設定 TextFrame 中的左邊距。 |
| [setMarginLeft(double value)](#setMarginLeft-double-) | 傳回或設定 TextFrame 中的左邊距。 |
| [getMarginRight()](#getMarginRight--) | 傳回或設定 TextFrame 中的右邊距。 |
| [setMarginRight(double value)](#setMarginRight-double-) | 傳回或設定 TextFrame 中的右邊距。 |
| [getMarginTop()](#getMarginTop--) | 傳回或設定 TextFrame 中的上邊距。 |
| [setMarginTop(double value)](#setMarginTop-double-) | 傳回或設定 TextFrame 中的上邊距。 |
| [getMarginBottom()](#getMarginBottom--) | 傳回或設定 TextFrame 中的下邊距。 |
| [setMarginBottom(double value)](#setMarginBottom-double-) | 傳回或設定 TextFrame 中的下邊距。 |
| [getTextVerticalType()](#getTextVerticalType--) | 傳回或設定垂直文字的類型。 |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | 傳回或設定垂直文字的類型。 |
| [getTextAnchorType()](#getTextAnchorType--) | 傳回或設定文字錨點類型。 |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | 傳回或設定文字錨點類型。 |
| [getAnchorCenter()](#getAnchorCenter--) | 判斷文字方塊是否在儲存格內置中。 |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | 判斷文字方塊是否在儲存格內置中。 |
| [getFirstRow()](#getFirstRow--) | 取得儲存格的第一列。 |
| [getFirstColumn()](#getFirstColumn--) | 取得儲存格的第一欄。 |
| [getColSpan()](#getColSpan--) | 傳回父表格之表格格線中，當前儲存格應跨越的網格欄數。 |
| [getRowSpan()](#getRowSpan--) | 傳回合併儲存格跨越的列數。 |
| [getTextFrame()](#getTextFrame--) | 傳回儲存格的文字框架。 |
| [getTable()](#getTable--) | 傳回儲存格的父 Table 物件。 |
| [isMergedCell()](#isMergedCell--) | 若儲存格與任何相鄰儲存格合併則傳回 true，否則傳回 false。 |
| [getCellFormat()](#getCellFormat--) | 傳回包含此儲存格格式屬性的 CellFormat 物件。 |
| [splitByColSpan(int index)](#splitByColSpan-int-) | 依欄索引將儲存格分割成兩個儲存格。 |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | 依列索引將儲存格分割成兩個儲存格。 |
| [splitByHeight(double height)](#splitByHeight-double-) | 依高度將儲存格分割。 |
| [splitByWidth(double width)](#splitByWidth-double-) | 依寬度將儲存格分割。 |
| [getSlide()](#getSlide--) | 傳回儲存格的父投影片。 |
| [getPresentation()](#getPresentation--) | 傳回儲存格的父簡報。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

傳回表格左側到儲存格左側的距離。 唯讀 double.

**返回:**
double
### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

傳回表格上側到儲存格上側的距離。 唯讀 double.

**返回:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

傳回儲存格所覆蓋的第一列索引。 唯讀 int.

**返回:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

傳回儲存格所覆蓋的第一欄索引。 唯讀 int.

**返回:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```

傳回儲存格的寬度。 唯讀 double.

**返回:**
double
### getHeight() {#getHeight--}
```
public final double getHeight()
```

傳回儲存格的高度。 唯讀 double.

**返回:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

傳回儲存格的最小高度。 這是所有被儲存格覆蓋的列之最小高度之和。 唯讀 double.

**返回:**
double
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

傳回或設定 TextFrame 中的左邊距。 可讀寫 double.

**返回:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

傳回或設定 TextFrame 中的左邊距。 可讀寫 double.

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

傳回或設定 TextFrame 中的右邊距。 可讀寫 double.

**返回:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

傳回或設定 TextFrame 中的右邊距。 可讀寫 double.

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

傳回或設定 TextFrame 中的上邊距。 可讀寫 double.

**返回:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

傳回或設定 TextFrame 中的上邊距。 可讀寫 double.

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

傳回或設定 TextFrame 中的下邊距。 可讀寫 double.

**返回:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

傳回或設定 TextFrame 中的下邊距。 可讀寫 double.

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

傳回或設定垂直文字的類型。 可讀寫 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**返回:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

傳回或設定垂直文字的類型。 可讀寫 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

傳回或設定文字錨點類型。 可讀寫 [TextAnchorType](../../com.aspose.slides/textanchortype).

**返回:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

傳回或設定文字錨點類型。 可讀寫 [TextAnchorType](../../com.aspose.slides/textanchortype).

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

判斷文字方塊是否在儲存格內置中。 可讀寫 boolean.

**返回:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

判斷文字方塊是否在儲存格內置中。 可讀寫 boolean.

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

取得儲存格的第一列。 唯讀 [IRow](../../com.aspose.slides/irow).

**返回:**
[IRow](../../com.aspose.slides/irow)
### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

取得儲存格的第一欄。 唯讀 [IColumn](../../com.aspose.slides/icolumn).

**返回:**
[IColumn](../../com.aspose.slides/icolumn)
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

傳回父表格之表格格線中，當前儲存格應跨越的網格欄數。 此屬性允許儲存格看起來已合併，因為它跨越了表格中其他儲存格的垂直邊界。 唯讀 int.

**返回:**
int
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

傳回合併儲存格跨越的列數。 此屬性與其他儲存格的 vMerge 屬性結合使用，以指定水平合併的起始儲存格。 唯讀 int.

**返回:**
int
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

傳回儲存格的文字框架。 唯讀 [ITextFrame](../../com.aspose.slides/itextframe).

**返回:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public final ITable getTable()
```

傳回儲存格的父 Table 物件。 唯讀 [ITable](../../com.aspose.slides/itable).

**返回:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

若儲存格與任何相鄰儲存格合併則傳回 true，否則傳回 false。 唯讀 boolean.

**返回:**
boolean
### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

傳回包含此儲存格格式屬性的 CellFormat 物件。 唯讀 [ICellFormat](../../com.aspose.slides/icellformat).

**返回:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

依欄索引將儲存格分割成兩個儲存格。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 欄的索引。 |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

依列索引將儲存格分割成兩個儲存格。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 列的索引。 |

### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

依高度將儲存格分割。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| height | double | 列的高度。 |

### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

依寬度將儲存格分割。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| width | double | 欄的寬度。 |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

傳回儲存格的父投影片。 唯讀 [IBaseSlide](../../com.aspose.slides/ibaseslide).

**返回:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

傳回儲存格的父簡報。 唯讀 [IPresentation](../../com.aspose.slides/ipresentation).

**返回:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。 唯讀 IDOMObject.

**返回:**
com.aspose.slides.IDOMObject