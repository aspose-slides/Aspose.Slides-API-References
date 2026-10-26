---
title: Table
second_title: Aspose.Slides for Android via Java API 参考
description: 表示幻灯片上的表。
type: docs
url: /zh/com.aspose.slides/table/
---
**继承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**所有实现的接口:**  
[com.aspose.slides.ITable](../../com.aspose.slides/itable)  
```
public final class Table extends GraphicalObject implements ITable
```

表示幻灯片上的表。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | 返回指定列和行索引处的单元格。 |
| [getRows()](#getRows--) | 返回行的集合。 |
| [getColumns()](#getColumns--) | 返回列的集合。 |
| [getTableFormat()](#getTableFormat--) | 返回包含此表格格式属性的 TableFormat 对象。 |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | 合并相邻的单元格。 |
| [getStylePreset()](#getStylePreset--) | 获取或设置内置表格样式。 |
| [setStylePreset(int value)](#setStylePreset-int-) | 获取或设置内置表格样式。 |
| [getRightToLeft()](#getRightToLeft--) | 确定表格是否采用从右到左的阅读顺序。 |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | 确定表格是否采用从右到左的阅读顺序。 |
| [getFirstRow()](#getFirstRow--) | 确定表格的第一行是否需要使用特殊格式绘制。 |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | 确定表格的第一行是否需要使用特殊格式绘制。 |
| [getFirstCol()](#getFirstCol--) | 确定表格的第一列是否需要使用特殊格式绘制。 |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | 确定表格的第一列是否需要使用特殊格式绘制。 |
| [getLastRow()](#getLastRow--) | 确定表格的最后一行是否需要使用特殊格式绘制。 |
| [setLastRow(boolean value)](#setLastRow-boolean-) | 确定表格的最后一行是否需要使用特殊格式绘制。 |
| [getLastCol()](#getLastCol--) | 确定表格的最后一列是否需要使用特殊格式绘制。 |
| [setLastCol(boolean value)](#setLastCol-boolean-) | 确定表格的最后一列是否需要使用特殊格式绘制。 |
| [getHorizontalBanding()](#getHorizontalBanding--) | 确定偶数行是否需要使用不同的格式绘制。 |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | 确定偶数行是否需要使用不同的格式绘制。 |
| [getVerticalBanding()](#getVerticalBanding--) | 确定偶数列是否需要使用不同的格式绘制。 |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | 确定偶数列是否需要使用不同的格式绘制。 |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | 为所有表格单元格的部分设置已定义的格式属性。 |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | 为所有表格单元格的段落设置已定义的段落格式属性。 |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | 为所有表格单元格的文本框设置已定义的文本框格式属性。 |
| [getFillFormat()](#getFillFormat--) | 返回包含表格填充格式的 TableFormat.FillFormat 对象。 |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

返回指定列和行索引处的单元格。只读 [Cell](../../com.aspose.slides/cell)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**返回值:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

返回行的集合。只读 [IRowCollection](../../com.aspose.slides/irowcollection)。

**返回值:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

返回列的集合。只读 [IColumnCollection](../../com.aspose.slides/icolumncollection)。

**返回值:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

返回包含此表格格式属性的 TableFormat 对象。只读 [ITableFormat](../../com.aspose.slides/itableformat)。

**返回值:**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

合并相邻的单元格。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | 要合并的单元格。 |
| cell2 | [ICell](../../com.aspose.slides/icell) | 要合并的单元格。 |
| allowSplitting | boolean | True 表示允许单元格拆分。 |

**返回值:**
[ICell](../../com.aspose.slides/icell) - 合并后的单元格。

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

获取或设置内置表格样式。读/写 [TableStylePreset](../../com.aspose.slides/tablestylepreset)。

**返回值:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

获取或设置内置表格样式。读/写 [TableStylePreset](../../com.aspose.slides/tablestylepreset)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

确定表格是否采用从右到左的阅读顺序。读写  boolean .

**返回值:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

确定表格是否采用从右到左的阅读顺序。读写  boolean .

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

确定表格的第一行是否需要使用特殊格式绘制。读/写  boolean .

**返回值:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

确定表格的第一行是否需要使用特殊格式绘制。读/写  boolean .

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

确定表格的第一列是否需要使用特殊格式绘制。读/写  boolean .

**返回值:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

确定表格的第一列是否需要使用特殊格式绘制。读/写  boolean .

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

确定表格的最后一行是否需要使用特殊格式绘制。读/写  boolean .

**返回值:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

确定表格的最后一行是否需要使用特殊格式绘制。读/写  boolean .

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

确定表格的最后一列是否需要使用特殊格式绘制。读/写  boolean .

**返回值:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

确定表格的最后一列是否需要使用特殊格式绘制。读/写  boolean .

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

确定偶数行是否需要使用不同的格式绘制。读/写  boolean .

**返回值:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

确定偶数行是否需要使用不同的格式绘制。读/写  boolean .

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

确定偶数列是否需要使用不同的格式绘制。读/写  boolean .

**返回值:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

确定偶数列是否需要使用不同的格式绘制。读/写  boolean .

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

为所有表格单元格的部分设置已定义的格式属性。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | 已设置必要属性的 IPortionFormat 对象。 |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

为所有表格单元格的段落设置已定义的段落格式属性。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | 已设置必要属性的 IParagraphFormat 对象。 |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

为所有表格单元格的文本框设置已定义的文本框格式属性。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | 已设置必要属性的 ITextFrameFormat 对象。 |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

返回包含表格填充格式的 TableFormat.FillFormat 对象。只读 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回值:**
[IFillFormat](../../com.aspose.slides/ifillformat)