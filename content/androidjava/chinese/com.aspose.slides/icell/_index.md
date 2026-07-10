---
title: ICell
second_title: Aspose.Slides for Android via Java API 参考
description: 表示表格中的单元格。
type: docs
url: /zh/com.aspose.slides/icell/
---
**所有实现的接口：**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

表示表格中的单元格。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | 返回表格左侧到单元格左侧的距离。 |
| [getOffsetY()](#getOffsetY--) | 返回表格顶部到单元格顶部的距离。 |
| [getFirstRowIndex()](#getFirstRowIndex--) | 返回单元格覆盖的第一行的索引。 |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | 返回单元格覆盖的第一列的索引。 |
| [getWidth()](#getWidth--) | 返回单元格的宽度。 |
| [getHeight()](#getHeight--) | 返回单元格的高度。 |
| [getMinimalHeight()](#getMinimalHeight--) | 返回单元格的最小高度。 |
| [getMarginLeft()](#getMarginLeft--) | 返回或设置 TextFrame 中的左边距。 |
| [setMarginLeft(double value)](#setMarginLeft-double-) | 返回或设置 TextFrame 中的左边距。 |
| [getMarginRight()](#getMarginRight--) | 返回或设置 TextFrame 中的右边距。 |
| [setMarginRight(double value)](#setMarginRight-double-) | 返回或设置 TextFrame 中的右边距。 |
| [getMarginTop()](#getMarginTop--) | 返回或设置 TextFrame 中的上边距。 |
| [setMarginTop(double value)](#setMarginTop-double-) | 返回或设置 TextFrame 中的上边距。 |
| [getMarginBottom()](#getMarginBottom--) | 返回或设置 TextFrame 中的下边距。 |
| [setMarginBottom(double value)](#setMarginBottom-double-) | 返回或设置 TextFrame 中的下边距。 |
| [getTextVerticalType()](#getTextVerticalType--) | 返回或设置垂直文本的类型。 |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | 返回或设置垂直文本的类型。 |
| [getTextAnchorType()](#getTextAnchorType--) | 返回或设置文本锚点类型。 |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | 返回或设置文本锚点类型。 |
| [getAnchorCenter()](#getAnchorCenter--) | 确定文本框是否居中于单元格内。 |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | 确定文本框是否居中于单元格内。 |
| [getFirstColumn()](#getFirstColumn--) | 获取单元格的第一列。 |
| [getFirstRow()](#getFirstRow--) | 获取单元格的第一行。 |
| [getColSpan()](#getColSpan--) | 返回父表格的表格网格中当前单元格跨越的列数。 |
| [getRowSpan()](#getRowSpan--) | 返回合并单元格跨越的行数。 |
| [getTextFrame()](#getTextFrame--) | 返回单元格的文本框架。 |
| [getTable()](#getTable--) | 返回单元格的父 Table 对象。 |
| [isMergedCell()](#isMergedCell--) | 如果单元格与任何相邻单元格合并则返回 true，否则返回 false。 |
| [getCellFormat()](#getCellFormat--) | 返回包含此单元格格式属性的 CellFormat 对象。 |
| [splitByColSpan(int index)](#splitByColSpan-int-) | 按列索引将单元格拆分为两个单元格。 |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | 按行索引将单元格拆分为两个单元格。 |
| [splitByHeight(double height)](#splitByHeight-double-) | 按高度拆分单元格。 |
| [splitByWidth(double width)](#splitByWidth-double-) | 按宽度拆分单元格。 |

### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

返回表格左侧到单元格左侧的距离。只读 double。

**返回：**
double

### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

返回表格顶部到单元格顶部的距离。只读 double。

**返回：**
double

### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```

返回单元格覆盖的第一行的索引。只读 int。

**返回：**
int

### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```

返回单元格覆盖的第一列的索引。只读 int。

**返回：**
int

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

返回单元格的宽度。只读 double。

**返回：**
double

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

返回单元格的高度。只读 double。

**返回：**
double

### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

返回单元格的最小高度。这是所有被单元格覆盖的行的最小高度之和。只读 double。

**返回：**
double

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

返回或设置 TextFrame 中的左边距。可读写 double。

**返回：**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

返回或设置 TextFrame 中的左边距。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

返回或设置 TextFrame 中的右边距。可读写 double。

**返回：**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

返回或设置 TextFrame 中的右边距。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

返回或设置 TextFrame 中的上边距。可读写 double。

**返回：**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

返回或设置 TextFrame 中的上边距。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

返回或设置 TextFrame 中的下边距。可读写 double。

**返回：**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

返回或设置 TextFrame 中的下边距。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

返回或设置垂直文本的类型。可读写 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**返回：**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

返回或设置垂直文本的类型。可读写 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

返回或设置文本锚点类型。可读写 [TextAnchorType](../../com.aspose.slides/textanchortype)。

**返回：**
byte

### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

返回或设置文本锚点类型。可读写 [TextAnchorType](../../com.aspose.slides/textanchortype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

确定文本框是否居中于单元格内。可读写 boolean。

**返回：**
boolean

### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

确定文本框是否居中于单元格内。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```

获取单元格的第一列。只读 [IColumn](../../com.aspose.slides/icolumn)。

**返回：**
[IColumn](../../com.aspose.slides/icolumn)

### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```

获取单元格的第一行。只读 [IRow](../../com.aspose.slides/irow)。

**返回：**
[IRow](../../com.aspose.slides/irow)

### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```

返回父表格的表格网格中当前单元格跨越的列数。此属性使单元格看起来像已合并，因为它跨越了表格中其他单元格的垂直边界。只读 int。

**返回：**
int

### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

返回合并单元格跨越的行数。此属性与其他单元格上的 vMerge 属性结合使用，以指定水平合并的起始单元格。只读 int。

**返回：**
int

### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

返回单元格的文本框架。只读 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTable() {#getTable--}
```
public abstract ITable getTable()
```

返回单元格的父 Table 对象。只读 [ITable](../../com.aspose.slides/itable)。

**返回：**
[ITable](../../com.aspose.slides/itable)

### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

如果单元格与任何相邻单元格合并则返回 true，否则返回 false。只读 boolean。

**返回：**
boolean

### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```

返回包含此单元格格式属性的 CellFormat 对象。只读 [ICellFormat](../../com.aspose.slides/icellformat)。

**返回：**
[ICellFormat](../../com.aspose.slides/icellformat)

### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```

按列索引将单元格拆分为两个单元格。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 列的索引。 |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

按行索引将单元格拆分为两个单元格。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 行的索引。 |

### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

按高度拆分单元格。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| height | double | 行的高度。 |

### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

按宽度拆分单元格。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | double | 列的宽度。 |