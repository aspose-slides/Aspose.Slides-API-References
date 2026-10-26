---
title: ITable
second_title: Aspose.Slides for Android via Java API 参考
description: 表示幻灯片中的表格。
type: docs
url: /zh/com.aspose.slides/itable/
---
**所有已实现的接口：**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

表示幻灯片中的表格。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | 返回指定列和行索引处的单元格。 |
| [getRows()](#getRows--) | 返回行的集合。 |
| [getColumns()](#getColumns--) | 返回列的集合。 |
| [getTableFormat()](#getTableFormat--) | 返回包含此表格格式属性的 TableFormat 对象。 |
| [getStylePreset()](#getStylePreset--) | 获取或设置内置表格样式。 |
| [setStylePreset(int value)](#setStylePreset-int-) | 获取或设置内置表格样式。 |
| [getRightToLeft()](#getRightToLeft--) | 确定表格是否具有从右到左的阅读顺序。 |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | 确定表格是否具有从右到左的阅读顺序。 |
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
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | 合并相邻单元格。 |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

返回指定列和行索引处的单元格。只读 [ICell](../../com.aspose.slides/icell)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**返回：**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

返回行的集合。只读 [IRowCollection](../../com.aspose.slides/irowcollection)。

**返回：**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

返回列的集合。只读 [IColumnCollection](../../com.aspose.slides/icolumncollection)。

**返回：**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

返回包含此表格格式属性的 TableFormat 对象。只读 [ITableFormat](../../com.aspose.slides/itableformat)。

**返回：**
[ITableFormat](../../com.aspose.slides/itableformat)

### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

获取或设置内置表格样式。可读写 [TableStylePreset](../../com.aspose.slides/tablestylepreset)。

**返回：**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

获取或设置内置表格样式。可读写 [TableStylePreset](../../com.aspose.slides/tablestylepreset)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

确定表格是否具有从右到左的阅读顺序。可读写 boolean。

**返回：**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

确定表格是否具有从右到左的阅读顺序。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

确定表格的第一行是否需要使用特殊格式绘制。可读写 boolean。

**返回：**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

确定表格的第一行是否需要使用特殊格式绘制。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

确定表格的第一列是否需要使用特殊格式绘制。可读写 boolean。

**返回：**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

确定表格的第一列是否需要使用特殊格式绘制。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

确定表格的最后一行是否需要使用特殊格式绘制。可读写 boolean。

**返回：**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

确定表格的最后一行是否需要使用特殊格式绘制。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

确定表格的最后一列是否需要使用特殊格式绘制。可读写 boolean。

**返回：**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

确定表格的最后一列是否需要使用特殊格式绘制。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

确定偶数行是否需要使用不同的格式绘制。可读写 boolean。

**返回：**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

确定偶数行是否需要使用不同的格式绘制。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

确定偶数列是否需要使用不同的格式绘制。可读写 boolean。

**返回：**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

确定偶数列是否需要使用不同的格式绘制。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

合并相邻单元格。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | 要合并的单元格。 |
| cell2 | [ICell](../../com.aspose.slides/icell) | 要合并的单元格。 |
| allowSplitting | boolean | 若为 true 则允许单元格拆分。 |

**返回：**
[ICell](../../com.aspose.slides/icell) - 合并的单元格。