---
title: IMathMatrix
second_title: Aspose.Slides for Android 之 Java API 參考
description: 指定由排成一或多列及欄的子元素組成的 Matrix 物件。
type: docs
url: /zh-hant/com.aspose.slides/imathmatrix/
---
**All Implemented Interfaces：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

指定 Matrix 物件，由排成一或多列及欄的子元素組成。需注意矩陣本身沒有內建分隔符號。若要在括號中放置矩陣，應使用分隔符物件 (IMathDelimiter)。可使用空參數在矩陣中建立空隙。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | 矩陣的元素 |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | 矩陣的元素 |
| [getRowCount()](#getRowCount--) | 矩陣的列數 |
| [getColumnCount()](#getColumnCount--) | 矩陣的欄數 |
| [getHidePlaceholders()](#getHidePlaceholders--) | 隱藏空矩陣元素的佔位符，預設值：false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | 隱藏空矩陣元素的佔位符，預設值：false |
| [getBaseJustification()](#getBaseJustification--) | 指定相對於周圍文字的垂直對齊方式。 |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 指定相對於周圍文字的垂直對齊方式。 |
| [getMinColumnWidth()](#getMinColumnWidth--) | 以 twips (1/20th of a point) 為單位的最小欄寬。間距 (also referred to to \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) 會加到 MinColumnWidth，以決定矩陣欄位總間距 (distance between the same edges of different columns)。 |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | 以 twips (1/20th of a point) 為單位的最小欄寬。間距 (also referred to to \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) 會加到 MinColumnWidth，以決定矩陣欄位總間距 (distance between the same edges of different columns)。 |
| [getColumnGapRule()](#getColumnGapRule--) | 矩陣欄位之間的水平間距類型；水平間距單位可以是 em 或點（以 twips 儲存）。 |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | 矩陣欄位之間的水平間距類型；水平間距單位可以是 em 或點（以 twips 儲存）。 |
| [getColumnGap()](#getColumnGap--) | 矩陣欄位之間的水平間距值；如果 ColumnGapRule 設為 3 (\"Exactly\")，則單位解釋為 twips（1/20th of a point）如果 ColumnGapRule 設為 4 (\"Multiple\")，則單位解釋為 0.5 em 的倍數。 |
| [setColumnGap(long value)](#setColumnGap-long-) | 矩陣欄位之間的水平間距值；如果 ColumnGapRule 設為 3 (\"Exactly\")，則單位解釋為 twips（1/20th of a point）如果 ColumnGapRule 設為 4 (\"Multiple\")，則單位解釋為 0.5 em 的倍數。 |
| [getRowGapRule()](#getRowGapRule--) | 矩陣列之間的垂直間距類型；垂直間距單位可以是行或點（以 twips 儲存）。 |
| [setRowGapRule(int value)](#setRowGapRule-int-) | 矩陣列之間的垂直間距類型；垂直間距單位可以是行或點（以 twips 儲存）。 |
| [getRowGap()](#getRowGap--) | 矩陣列之間的垂直間距值；如果 RowGapRule 設為 3 (\"Exactly\")，則單位解釋為 twips（1/20th of a point）如果 RowGapRule 設為 4 (\"Multiple\")，則單位解釋為 half-lines。 |
| [setRowGap(long value)](#setRowGap-long-) | 矩陣列之間的垂直間距值；如果 RowGapRule 設為 3 (\"Exactly\")，則單位解釋為 twips（1/20th of a point）如果 RowGapRule 設為 4 (\"Multiple\")，則單位解釋為 half-lines。 |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | 取得指定欄位的水平對齊方式 |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | 設定指定欄位的水平對齊方式 |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | 設定指定欄位的水平對齊方式 |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | 在指定位置前插入新列，新列的所有元素初始為 null。 |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | 在指定位置後插入新列，新列的所有元素初始為 null。 |
| [deleteRow(int rowIndex)](#deleteRow-int-) | 刪除指定的列 |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | 在指定位置前插入新欄，欄位的所有元素初始為 null。 |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | 在指定位置後插入新欄，欄位的所有元素初始為 null。 |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | 刪除指定的欄位 |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

矩陣的元素

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parameters：**
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | 取得項目的列的零基索引 |
| column | int | 取得項目的欄的零基索引 |

**Returns：**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

矩陣的元素

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parameters：**
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | 取得項目的列的零基索引 |
| column | int | 取得項目的欄的零基索引 |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
```

矩陣的列數

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Returns：**
int
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

矩陣的欄數

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Returns：**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

隱藏空矩陣元素的佔位符，預設值：false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Returns：**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

隱藏空矩陣元素的佔位符，預設值：false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Parameters：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

指定相對於周圍文字的垂直對齊方式。可能的值有 top、bottom 和 center。預設：Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Returns：**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

指定相對於周圍文字的垂直對齊方式。可能的值有 top、bottom 和 center。預設：Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Parameters：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public abstract long getMinColumnWidth()
```

以 twips (1/20th of a point) 為單位的最小欄寬。間距 (also referred to to \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) 會加到 MinColumnWidth，以決定矩陣欄位總間距 (distance between the same edges of different columns)。預設值：0。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Returns：**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

以 twips (1/20th of a point) 為單位的最小欄寬。間距 (also referred to to \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) 會加到 MinColumnWidth，以決定矩陣欄位總間距 (distance between the same edges of different columns)。預設值：0。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Parameters：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public abstract int getColumnGapRule()
```

矩陣欄位之間的水平間距類型；水平間距單位可以是 em 或點（以 twips 儲存）。預設值：SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Returns：**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```

矩陣欄位之間的水平間距類型；水平間距單位可以是 em 或點（以 twips 儲存）。預設值：SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parameters：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public abstract long getColumnGap()
```

矩陣欄位之間的水平間距值；如果 ColumnGapRule 設為 3 (\"Exactly\")，則單位解釋為 twips（1/20th of a point）如果 ColumnGapRule 設為 4 (\"Multiple\")，則單位解釋為 0.5 em 的倍數。在其他情況下忽略。預設值：0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Returns：**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

矩陣欄位之間的水平間距值；如果 ColumnGapRule 設為 3 (\"Exactly\")，則單位解釋為 twips（1/20th of a point）如果 ColumnGapRule 設為 4 (\"Multiple\")，則單位解釋為 0.5 em 的倍數。在其他情況下忽略。預設值：0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Parameters：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public abstract int getRowGapRule()
```

矩陣列之間的垂直間距類型；垂直間距單位可以是行或點（以 twips 儲存）。預設值：SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Returns：**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

矩陣列之間的垂直間距類型；垂直間距單位可以是行或點（以 twips 儲存）。預設值：SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parameters：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public abstract long getRowGap()
```

矩陣列之間的垂直間距值；如果 RowGapRule 設為 3 (\"Exactly\")，則單位解釋為 twips（1/20th of a point）如果 RowGapRule 設為 4 (\"Multiple\")，則單位解釋為 half-lines。預設值：0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Returns：**
long
### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```

矩陣列之間的垂直間距值；如果 RowGapRule 設為 3 (\"Exactly\")，則單位解釋為 twips（1/20th of a point）如果 RowGapRule 設為 4 (\"Multiple\")，則單位解釋為 half-lines。預設值：0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Parameters：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

取得指定欄位的水平對齊方式

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parameters：**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | 零基欄索引 |

**Returns：**
int - 指定欄位的水平對齊方式
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

設定指定欄位的水平對齊方式

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Parameters：**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | 零基欄索引 |
| val | int | 指定欄位的水平對齊方式新值 |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

設定指定欄位的水平對齊方式

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parameters：**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | 要設定對齊的第一個欄位之零基索引 |
| columnsCount | long | 要設定對齊的欄位數量 |
| val | int | 指定欄位的水平對齊方式新值 |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

在指定位置前插入新列，新列的所有元素初始為 null。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Parameters：**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | 要在其前插入新列的列索引 |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

在指定位置後插入新列，新列的所有元素初始為 null。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Parameters：**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | 要在其後插入新列的列索引 |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

刪除指定的列

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Parameters：**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | 要刪除之列的零基索引。 |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

在指定位置前插入新欄，欄位的所有元素初始為 null。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
```

**Parameters：**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | 要在其前插入新欄的欄索引 |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

在指定位置後插入新欄，欄位的所有元素初始為 null。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Parameters：**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | 要在其後插入新欄的欄索引 |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

刪除指定的欄位

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parameters：**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | 要刪除之欄的零基索引。 |