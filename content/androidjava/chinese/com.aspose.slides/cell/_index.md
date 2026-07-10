---
title: Cell
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 表示表格中的单元格。
type: docs
url: /zh/com.aspose.slides/cell/
---
**继承:**  
java.lang.Object

**已实现的接口:**  
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)  
```
public class Cell implements IDOMObject, ICell
```

表示表格中的单元格。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | 返回表格左侧到单元格左侧的距离。 |
| [getOffsetY()](#getOffsetY--) | 返回表格上侧到单元格上侧的距离。 |
| [getFirstRowIndex()](#getFirstRowIndex--) | 返回单元格覆盖的第一行的索引。 |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | 返回单元格覆盖的第一列的索引。 |
| [getWidth()](#getWidth--) | 返回单元格的宽度。 |
| [getHeight()](#getHeight--) | 返回单元格的高度。 |
| [getMinimalHeight()](#getMinimalHeight--) | 返回单元格的最小高度。 |
| [getMarginLeft()](#getMarginLeft--) | 获取或设置 TextFrame 中的左边距。 |
| [setMarginLeft(double value)](#setMarginLeft-double-) | 获取或设置 TextFrame 中的左边距。 |
| [getMarginRight()](#getMarginRight--) | 获取或设置 TextFrame 中的右边距。 |
| [setMarginRight(double value)](#setMarginRight-double-) | 获取或设置 TextFrame 中的右边距。 |
| [getMarginTop()](#getMarginTop--) | 获取或设置 TextFrame 中的上边距。 |
| [setMarginTop(double value)](#setMarginTop-double-) | 获取或设置 TextFrame 中的上边距。 |
| [getMarginBottom()](#getMarginBottom--) | 获取或设置 TextFrame 中的下边距。 |
| [setMarginBottom(double value)](#setMarginBottom-double-) | 获取或设置 TextFrame 中的下边距。 |
| [getTextVerticalType()](#getTextVerticalType--) | 获取或设置垂直文本的类型。 |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | 获取或设置垂直文本的类型。 |
| [getTextAnchorType()](#getTextAnchorType--) | 获取或设置文本锚点类型。 |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | 获取或设置文本锚点类型。 |
| [getAnchorCenter()](#getAnchorCenter--) | 判断文本框是否在单元格内居中。 |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | 判断文本框是否在单元格内居中。 |
| [getFirstRow()](#getFirstRow--) | 获取单元格的第一行。 |
| [getFirstColumn()](#getFirstColumn--) | 获取单元格的第一列。 |
| [getColSpan()](#getColSpan--) | 返回父表格网格中当前单元格跨越的列数。 |
| [getRowSpan()](#getRowSpan--) | 返回合并单元格跨越的行数。 |
| [getTextFrame()](#getTextFrame--) | 返回单元格的 TextFrame。 |
| [getTable()](#getTable--) | 返回单元格所属的父 Table 对象。 |
| [isMergedCell()](#isMergedCell--) | 如果单元格与任何相邻单元格合并则返回 true，否则返回 false。 |
| [getCellFormat()](#getCellFormat--) | 返回包含此单元格格式属性的 CellFormat 对象。 |
| [splitByColSpan(int index)](#splitByColSpan-int-) | 按列索引将单元格拆分为两个单元格。 |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | 按行索引将单元格拆分为两个单元格。 |
| [splitByHeight(double height)](#splitByHeight-double-) | 按高度拆分单元格。 |
| [splitByWidth(double width)](#splitByWidth-double-) | 按宽度拆分单元格。 |
| [getSlide()](#getSlide--) | 返回单元格所在的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回单元格所在的父演示文稿。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

返回表格左侧到单元格左侧的距离。只读 double。

**返回：**
double

### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

返回表格上侧到单元格上侧的距离。只读 double。

**返回：**
double

### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

返回单元格覆盖的第一行的索引。只读 int。

**返回：**
int

### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

返回单元格覆盖的第一列的索引。只读 int。

**返回：**
int

### getWidth() {#getWidth--}
```
public final double getWidth()
```

返回单元格的宽度。只读 double。

**返回：**
double

### getHeight() {#getHeight--}
```
public final double getHeight()
```

返回单元格的高度。只读 double。

**返回：**
double

### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

返回单元格的最小高度。这是所有被单元格覆盖的行最小高度之和。只读 double。

**返回：**
double

### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

获取或设置 TextFrame 中的左边距。读写 double。

**返回：**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

获取或设置 TextFrame 中的左边距。读写 double。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

获取或设置 TextFrame 中的右边距。读写 double。

**返回：**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

获取或设置 TextFrame 中的右边距。读写 double。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

获取或设置 TextFrame 中的上边距。读写 double。

**返回：**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

获取或设置 TextFrame 中的上边距。读写 double。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

获取或设置 TextFrame 中的下边距。读写 double。

**返回：**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

获取或设置 TextFrame 中的下边距。读写 double。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

获取或设置垂直文本的类型。读写 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**返回：**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

获取或设置垂直文本的类型。读写 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

获取或设置文本锚点类型。读写 [TextAnchorType](../../com.aspose.slides/textanchortype)。

**返回：**
byte

### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

获取或设置文本锚点类型。读写 [TextAnchorType](../../com.aspose.slides/textanchortype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

判断文本框是否在单元格内居中。读写 boolean。

**返回：**
boolean

### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

判断文本框是否在单元格内居中。读写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

获取单元格的第一行。只读 [IRow](../../com.aspose.slides/irow)。

**返回：**
[IRow](../../com.aspose.slides/irow)

### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

获取单元格的第一列。只读 [IColumn](../../com.aspose.slides/icolumn)。

**返回：**
[IColumn](../../com.aspose.slides/icolumn)

### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

返回父表格网格中当前单元格跨越的列数。此属性使单元格看起来被合并，跨越其他单元格的垂直边界。只读 int。

**返回：**
int

### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

返回合并单元格跨越的行数。此属性与其他单元格的 vMerge 属性结合使用，以指定水平合并的起始单元格。只读 int。

**返回：**
int

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

返回单元格的 TextFrame。只读 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTable() {#getTable--}
```
public final ITable getTable()
```

返回单元格所属的父 Table 对象。只读 [ITable](../../com.aspose.slides/itable)。

**返回：**
[ITable](../../com.aspose.slides/itable)

### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

如果单元格与任何相邻单元格合并则返回 true，否则返回 false。只读 boolean。

**返回：**
boolean

### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

返回包含此单元格格式属性的 CellFormat 对象。只读 [ICellFormat](../../com.aspose.slides/icellformat)。

**返回：**
[ICellFormat](../../com.aspose.slides/icellformat)

### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

按列索引将单元格拆分为两个单元格。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 列索引。 |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

按行索引将单元格拆分为两个单元格。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 行索引。 |

### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

按高度拆分单元格。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| height | double | 行的高度。 |

### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

按宽度拆分单元格。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | double | 列的宽度。 |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回单元格所在的父幻灯片。只读 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**返回：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回单元格所在的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject