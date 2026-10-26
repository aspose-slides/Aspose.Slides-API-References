---
title: Cell
second_title: Aspose.Sildes for PHP 通过 Java API 参考
description: 
type: docs

url: /zh/aspose.slides/cell/
---
## Cell 类

表示表格中的单元格。

### getAnchorCenter {#getAnchorCenter}

| 名称 | 描述 |
| --- | --- |
| getAnchorCenter () | 确定文本框是否在单元格内部居中。可读写 boolean。 |

**返回：**
boolean


---


### getCellFormat {#getCellFormat}

| 名称 | 描述 |
| --- | --- |
| getCellFormat () | 返回包含此单元格格式属性的 CellFormat 对象。只读 ICellFormat。 |

**返回：**
[CellFormat](../cellformat)


---


### getColSpan {#getColSpan}

| 名称 | 描述 |
| --- | --- |
| getColSpan () | 返回父表格网格中当前单元格应跨越的网格列数。此属性能够让单元格看起来被合并，因为它跨越了表格中其他单元格的垂直边界。只读 int。 |

**返回：**
int


---


### getFirstColumn {#getFirstColumn}

| 名称 | 描述 |
| --- | --- |
| getFirstColumn () | 获取单元格的第一列。只读 IColumn。 |

**返回：**
[Column](../column)


---


### getFirstColumnIndex {#getFirstColumnIndex}

| 名称 | 描述 |
| --- | --- |
| getFirstColumnIndex () | 返回单元格所覆盖的第一列的索引。只读 int。 |

**返回：**
int


---


### getFirstRow {#getFirstRow}

| 名称 | 描述 |
| --- | --- |
| getFirstRow () | 获取单元格的第一行。只读 IRow。 |

**返回：**
[Row](../row)


---


### getFirstRowIndex {#getFirstRowIndex}

| 名称 | 描述 |
| --- | --- |
| getFirstRowIndex () | 返回单元格所覆盖的第一行的索引。只读 int。 |

**返回：**
int


---


### getHeight {#getHeight}

| 名称 | 描述 |
| --- | --- |
| getHeight () | 返回单元格的高度。只读 double。 |

**返回：**
double


---


### getMarginBottom {#getMarginBottom}

| 名称 | 描述 |
| --- | --- |
| getMarginBottom () | 返回或设置 TextFrame 的底部边距。可读写 double。 |

**返回：**
double


---


### getMarginLeft {#getMarginLeft}

| 名称 | 描述 |
| --- | --- |
| getMarginLeft () | 返回或设置 TextFrame 的左侧边距。可读写 double。 |

**返回：**
double


---


### getMarginRight {#getMarginRight}

| 名称 | 描述 |
| --- | --- |
| getMarginRight () | 返回或设置 TextFrame 的右侧边距。可读写 double。 |

**返回：**
double


---


### getMarginTop {#getMarginTop}

| 名称 | 描述 |
| --- | --- |
| getMarginTop () | 返回或设置 TextFrame 的顶部边距。可读写 double。 |

**返回：**
double


---


### getMinimalHeight {#getMinimalHeight}

| 名称 | 描述 |
| --- | --- |
| getMinimalHeight () | 返回单元格的最小高度。这是该单元格覆盖的所有行的最小高度之和。只读 double。 |

**返回：**
double


---


### getOffsetX {#getOffsetX}

| 名称 | 描述 |
| --- | --- |
| getOffsetX () | 返回表格左侧到单元格左侧的距离。只读 double。 |

**返回：**
double


---


### getOffsetY {#getOffsetY}

| 名称 | 描述 |
| --- | --- |
| getOffsetY () | 返回表格顶部到单元格顶部的距离。只读 double。 |

**返回：**
double


---


### getPresentation {#getPresentation}

| 名称 | 描述 |
| --- | --- |
| getPresentation () | 返回单元格所属的父演示文稿。只读 IPresentation。 |

**返回：**
[Presentation](../presentation)


---


### getRowSpan {#getRowSpan}

| 名称 | 描述 |
| --- | --- |
| getRowSpan () | 返回合并单元格跨越的行数。此属性与其他单元格的 vMerge 属性结合使用，以指定水平合并的起始单元格。只读 int。 |

**返回：**
int


---


### getSlide {#getSlide}

| 名称 | 描述 |
| --- | --- |
| getSlide () | 返回单元格所属的父幻灯片。只读 IBaseSlide。 |

**返回：**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getTable {#getTable}

| 名称 | 描述 |
| --- | --- |
| getTable () | 返回单元格所属的父 Table 对象。只读 ITable。 |

**返回：**
[Table](../table)


---


### getTextAnchorType {#getTextAnchorType}

| 名称 | 描述 |
| --- | --- |
| getTextAnchorType () | 返回或设置文本锚点类型。可读写 TextAnchorType。 |

**返回：**
byte


---


### getTextFrame {#getTextFrame}

| 名称 | 描述 |
| --- | --- |
| getTextFrame () | 返回单元格的文本框。只读 ITextFrame。 |

**返回：**
[TextFrame](../textframe)


---


### getTextVerticalType {#getTextVerticalType}

| 名称 | 描述 |
| --- | --- |
| getTextVerticalType () | 返回或设置垂直文本类型。可读写 TextVerticalType。 |

**返回：**
byte


---


### getWidth {#getWidth}

| 名称 | 描述 |
| --- | --- |
| getWidth () | 返回单元格的宽度。只读 double。 |

**返回：**
double


---


### isMergedCell {#isMergedCell}

| 名称 | 描述 |
| --- | --- |
| isMergedCell () | 如果单元格与任何相邻单元格合并则返回 true，否则返回 false。只读 boolean。 |

**返回：**
boolean


---


### setAnchorCenter {#setAnchorCenter}

| 名称 | 描述 |
| --- | --- |
| setAnchorCenter (boolean) | 确定文本框是否在单元格内部居中。可读写 boolean。 |

**返回：**
void


---


### setMarginBottom {#setMarginBottom}

| 名称 | 描述 |
| --- | --- |
| setMarginBottom (double) | 返回或设置 TextFrame 的底部边距。可读写 double。 |

**返回：**
void


---


### setMarginLeft {#setMarginLeft}

| 名称 | 描述 |
| --- | --- |
| setMarginLeft (double) | 返回或设置 TextFrame 的左侧边距。可读写 double。 |

**返回：**
void


---


### setMarginRight {#setMarginRight}

| 名称 | 描述 |
| --- | --- |
| setMarginRight (double) | 返回或设置 TextFrame 的右侧边距。可读写 double。 |

**返回：**
void


---


### setMarginTop {#setMarginTop}

| 名称 | 描述 |
| --- | --- |
| setMarginTop (double) | 返回或设置 TextFrame 的顶部边距。可读写 double。 |

**返回：**
void


---


### setTextAnchorType {#setTextAnchorType}

| 名称 | 描述 |
| --- | --- |
| setTextAnchorType (byte) | 返回或设置文本锚点类型。可读写 TextAnchorType。 |

**返回：**
void


---


### setTextVerticalType {#setTextVerticalType}

| 名称 | 描述 |
| --- | --- |
| setTextVerticalType (byte) | 返回或设置垂直文本类型。可读写 TextVerticalType。 |

**返回：**
void


---


### splitByColSpan {#splitByColSpan}

| 名称 | 描述 |
| --- | --- |
| splitByColSpan (int) | 按列索引将单元格拆分为两个单元格。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 列的索引。 |

**返回：**
void


---


### splitByHeight {#splitByHeight}

| 名称 | 描述 |
| --- | --- |
| splitByHeight (double) | 按高度拆分单元格。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| height | double | 行的高度。 |

**返回：**
void


---


### splitByRowSpan {#splitByRowSpan}

| 名称 | 描述 |
| --- | --- |
| splitByRowSpan (int) | 按行索引将单元格拆分为两个单元格。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 行的索引。 |

**返回：**
void


---


### splitByWidth {#splitByWidth}

| 名称 | 描述 |
| --- | --- |
| splitByWidth (double) | 按宽度拆分单元格。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| width | double | 列的宽度。 |

**返回：**
void


---