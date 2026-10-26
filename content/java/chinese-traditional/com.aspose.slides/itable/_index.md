---
title: ITable
second_title: Aspose.Slides for Java API 參考
description: 表示投影片上的表格。
type: docs
url: /zh-hant/com.aspose.slides/itable/
---
**所有已實作的介面：**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

代表投影片上的表格。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | 傳回指定欄與列索引處的儲存格。 |
| [getRows()](#getRows--) | 傳回列的集合。 |
| [getColumns()](#getColumns--) | 傳回欄的集合。 |
| [getTableFormat()](#getTableFormat--) | 傳回包含此表格格式屬性的 TableFormat 物件。 |
| [getStylePreset()](#getStylePreset--) | 取得或設定內建表格樣式。 |
| [setStylePreset(int value)](#setStylePreset-int-) | 取得或設定內建表格樣式。 |
| [getRightToLeft()](#getRightToLeft--) | 判斷表格是否具有由右至左的閱讀順序。 |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | 判斷表格是否具有由右至左的閱讀順序。 |
| [getFirstRow()](#getFirstRow--) | 判斷表格的第一列是否需以特殊格式繪製。 |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | 判斷表格的第一列是否需以特殊格式繪製。 |
| [getFirstCol()](#getFirstCol--) | 判斷表格的第一欄是否需以特殊格式繪製。 |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | 判斷表格的第一欄是否需以特殊格式繪製。 |
| [getLastRow()](#getLastRow--) | 判斷表格的最後一列是否需以特殊格式繪製。 |
| [setLastRow(boolean value)](#setLastRow-boolean-) | 判斷表格的最後一列是否需以特殊格式繪製。 |
| [getLastCol()](#getLastCol--) | 判斷表格的最後一欄是否需以特殊格式繪製。 |
| [setLastCol(boolean value)](#setLastCol-boolean-) | 判斷表格的最後一欄是否需以特殊格式繪製。 |
| [getHorizontalBanding()](#getHorizontalBanding--) | 判斷偶數列是否需以不同格式繪製。 |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | 判斷偶數列是否需以不同格式繪製。 |
| [getVerticalBanding()](#getVerticalBanding--) | 判斷偶數欄是否需以不同格式繪製。 |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | 判斷偶數欄是否需以不同格式繪製。 |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | 合併相鄰的儲存格。 |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

傳回指定欄與列索引處的儲存格。唯讀 [ICell](../../com.aspose.slides/icell)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**傳回:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

傳回列的集合。唯讀 [IRowCollection](../../com.aspose.slides/irowcollection)。

**傳回:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

傳回欄的集合。唯讀 [IColumnCollection](../../com.aspose.slides/icolumncollection)。

**傳回:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

傳回包含此表格格式屬性的 TableFormat 物件。唯讀 [ITableFormat](../../com.aspose.slides/itableformat)。

**傳回:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

取得或設定內建表格樣式。可讀寫 [TableStylePreset](../../com.aspose.slides/tablestylepreset)。

**傳回:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

取得或設定內建表格樣式。可讀寫 [TableStylePreset](../../com.aspose.slides/tablestylepreset)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

判斷表格是否具有由右至左的閱讀順序。可讀寫 boolean。

**傳回:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

判斷表格是否具有由右至左的閱讀順序。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

判斷表格的第一列是否需以特殊格式繪製。可讀寫 boolean。

**傳回:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

判斷表格的第一列是否需以特殊格式繪製。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

判斷表格的第一欄是否需以特殊格式繪製。可讀寫 boolean。

**傳回:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

判斷表格的第一欄是否需以特殊格式繪製。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

判斷表格的最後一列是否需以特殊格式繪製。可讀寫 boolean。

**傳回:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

判斷表格的最後一列是否需以特殊格式繪製。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

判斷表格的最後一欄是否需以特殊格式繪製。可讀寫 boolean。

**傳回:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

判斷表格的最後一欄是否需以特殊格式繪製。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

判斷偶數列是否需以不同格式繪製。可讀寫 boolean。

**傳回:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

判斷偶數列是否需以不同格式繪製。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

判斷偶數欄是否需以不同格式繪製。可讀寫 boolean。

**傳回:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

判斷偶數欄是否需以不同格式繪製。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

合併相鄰的儲存格。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | 要合併的儲存格。 |
| cell2 | [ICell](../../com.aspose.slides/icell) | 要合併的儲存格。 |
| allowSplitting | boolean | 設為 true 時允許儲存格分割。 |

**傳回:**
[ICell](../../com.aspose.slides/icell) - 合併後的儲存格。