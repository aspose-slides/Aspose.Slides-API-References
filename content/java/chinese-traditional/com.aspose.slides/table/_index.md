---
title: Table
second_title: Aspose.Slides for Java API 參考
description: 表示投影片上的表格。
type: docs
url: /zh-hant/com.aspose.slides/table/
---
**繼承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**所有已實作的介面：**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

表示投影片上的表格。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | 傳回在指定的欄與列索引處的儲存格。 |
| [getRows()](#getRows--) | 傳回列的集合。 |
| [getColumns()](#getColumns--) | 傳回欄的集合。 |
| [getTableFormat()](#getTableFormat--) | 傳回包含此表格格式屬性的 TableFormat 物件。 |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | 合併相鄰的儲存格。 |
| [getStylePreset()](#getStylePreset--) | 取得或設定內建表格樣式。 |
| [setStylePreset(int value)](#setStylePreset-int-) | 取得或設定內建表格樣式。 |
| [getRightToLeft()](#getRightToLeft--) | 判斷表格是否採用由右至左的閱讀順序。 |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | 判斷表格是否採用由右至左的閱讀順序。 |
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
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | 設定已定義的部分格式屬性至所有表格儲存格的部分。 |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | 設定已定義的段落格式屬性至所有表格儲存格的段落。 |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | 設定已定義的文字框格式屬性至所有表格儲存格的文字框。 |
| [getFillFormat()](#getFillFormat--) | 傳回包含此表格填充格式的 TableFormat.FillFormat 物件。 |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

傳回在指定的欄與列索引處的儲存格。唯讀 [Cell](../../com.aspose.slides/cell)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**傳回：**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

傳回列的集合。唯讀 [IRowCollection](../../com.aspose.slides/irowcollection)。

**傳回：**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

傳回欄的集合。唯讀 [IColumnCollection](../../com.aspose.slides/icolumncollection)。

**傳回：**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

傳回包含此表格格式屬性的 TableFormat 物件。唯讀 [ITableFormat](../../com.aspose.slides/itableformat)。

**傳回：**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

合併相鄰的儲存格。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | 要合併的儲存格。 |
| cell2 | [ICell](../../com.aspose.slides/icell) | 要合併的儲存格。 |
| allowSplitting | boolean | True 以允許儲存格分割。 |

**傳回：**
[ICell](../../com.aspose.slides/icell) - 合併後的儲存格。

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

取得或設定內建表格樣式。讀寫 [TableStylePreset](../../com.aspose.slides/tablestylepreset)。

**傳回：**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

取得或設定內建表格樣式。讀寫 [TableStylePreset](../../com.aspose.slides/tablestylepreset)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

判斷表格是否採用由右至左的閱讀順序。讀寫  boolean 。

**傳回：**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

判斷表格是否採用由右至左的閱讀順序。讀寫  boolean 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

判斷表格的第一列是否需要以特殊格式繪製。讀寫  boolean 。

**傳回：**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

判斷表格的第一列是否需要以特殊格式繪製。讀寫  boolean 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

判斷表格的第一欄是否需要以特殊格式繪製。讀寫  boolean 。

**傳回：**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

判斷表格的第一欄是否需要以特殊格式繪製。讀寫  boolean 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

判斷表格的最後一列是否需要以特殊格式繪製。讀寫  boolean 。

**傳回：**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

判斷表格的最後一列是否需要以特殊格式繪製。讀寫  boolean 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

判斷表格的最後一欄是否需要以特殊格式繪製。讀寫  boolean 。

**傳回：**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

判斷表格的最後一欄是否需要以特殊格式繪製。讀寫  boolean 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

判斷偶數列是否需要以不同的格式繪製。讀寫  boolean 。

**傳回：**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

判斷偶數列是否需要以不同的格式繪製。讀寫  boolean 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

判斷偶數欄是否需要以不同的格式繪製。讀寫  boolean 。

**傳回：**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

判斷偶數欄是否需要以不同的格式繪製。讀寫  boolean 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

設定已定義的部分格式屬性至所有表格儲存格的部分。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | 已設定必要屬性的 IPortionFormat 物件。 |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

設定已定義的段落格式屬性至所有表格儲存格的段落。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | 已設定必要屬性的 IParagraphFormat 物件。 |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

設定已定義的文字框格式屬性至所有表格儲存格的文字框。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | 已設定必要屬性的 ITextFrameFormat 物件。 |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

傳回包含此表格填充格式的 TableFormat.FillFormat 物件。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**傳回：**
[IFillFormat](../../com.aspose.slides/ifillformat)