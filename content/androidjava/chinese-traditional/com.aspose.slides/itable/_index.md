---
title: ITable
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示投影片上的表格。
type: docs
url: /zh-hant/com.aspose.slides/itable/
---
**所有已實作的介面:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

表示投影片上的表格。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | 返回指定欄位與列索引處的 cell。 |
| [getRows()](#getRows--) | 返回 rows 的集合。 |
| [getColumns()](#getColumns--) | 返回 columns 的集合。 |
| [getTableFormat()](#getTableFormat--) | 返回包含此表格格式屬性的 TableFormat 物件。 |
| [getStylePreset()](#getStylePreset--) | 取得或設定內建表格樣式。 |
| [setStylePreset(int value)](#setStylePreset-int-) | 取得或設定內建表格樣式。 |
| [getRightToLeft()](#getRightToLeft--) | 判斷表格是否具有從右至左的閱讀順序。 |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | 判斷表格是否具有從右至左的閱讀順序。 |
| [getFirstRow()](#getFirstRow--) | 判斷表格的第一列是否需要以特殊格式繪製。 |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | 判斷表格的第一列是否需要以特殊格式繪製。 |
| [getFirstCol()](#getFirstCol--) | 判斷表格的第一欄是否需要以特殊格式繪製。 |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | 判斷表格的第一欄是否需要以特殊格式繪製。 |
| [getLastRow()](#getLastRow--) | 判斷表格的最後一列是否需要以特殊格式繪製。 |
| [setLastRow(boolean value)](#setLastRow-boolean-) | 判斷表格的最後一列是否需要以特殊格式繪製。 |
| [getLastCol()](#getLastCol--) | 判斷表格的最後一欄是否需要以特殊格式繪製。 |
| [setLastCol(boolean value)](#setLastCol-boolean-) | 判斷表格的最後一欄是否需要以特殊格式繪製。 |
| [getHorizontalBanding()](#getHorizontalBanding--) | 判斷偶數列是否需要以不同的格式繪製。 |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | 判斷偶數列是否需要以不同的格式繪製。 |
| [getVerticalBanding()](#getVerticalBanding--) | 判斷偶數欄是否需要以不同的格式繪製。 |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | 判斷偶數欄是否需要以不同的格式繪製。 |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | 合併相鄰的 cells。 |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

返回指定欄位與列索引處的 cell。唯讀 [ICell](../../com.aspose.slides/icell)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**回傳:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

返回 rows 的集合。唯讀 [IRowCollection](../../com.aspose.slides/irowcollection)。

**回傳:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

返回 columns 的集合。唯讀 [IColumnCollection](../../com.aspose.slides/icolumncollection)。

**回傳:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

返回包含此表格格式屬性的 TableFormat 物件。唯讀 [ITableFormat](../../com.aspose.slides/itableformat)。

**回傳:**
[ITableFormat](../../com.aspose.slides/itableformat)

### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

取得或設定內建表格樣式。讀寫 [TableStylePreset](../../com.aspose.slides/tablestylepreset)。

**回傳:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

取得或設定內建表格樣式。讀寫 [TableStylePreset](../../com.aspose.slides/tablestylepreset)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

判斷表格是否具有從右至左的閱讀順序。讀寫布林值。

**回傳:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

判斷表格是否具有從右至左的閱讀順序。讀寫布林值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

判斷表格的第一列是否需要以特殊格式繪製。讀寫布林值。

**回傳:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

判斷表格的第一列是否需要以特殊格式繪製。讀寫布林值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

判斷表格的第一欄是否需要以特殊格式繪製。讀寫布林值。

**回傳:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

判斷表格的第一欄是否需要以特殊格式繪製。讀寫布林值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

判斷表格的最後一列是否需要以特殊格式繪製。讀寫布林值。

**回傳:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

判斷表格的最後一列是否需要以特殊格式繪製。讀寫布林值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

判斷表格的最後一欄是否需要以特殊格式繪製。讀寫布林值。

**回傳:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

判斷表格的最後一欄是否需要以特殊格式繪製。讀寫布林值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

判斷偶數列是否需要以不同的格式繪製。讀寫布林值。

**回傳:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

判斷偶數列是否需要以不同的格式繪製。讀寫布林值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

判斷偶數欄是否需要以不同的格式繪製。讀寫布林值。

**回傳:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

判斷偶數欄是否需要以不同的格式繪製。讀寫布林值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

合併相鄰的 cells。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Cell to merge. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cell to merge. |
| allowSplitting | boolean | True to allow cells splitting. |

**回傳:**
[ICell](../../com.aspose.slides/icell) - Merged cell.