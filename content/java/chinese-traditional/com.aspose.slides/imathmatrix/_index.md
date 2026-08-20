---
title: IMathMatrix
second_title: Aspose.Slides for Java API 參考
description: 指定由子元素排列在一個或多個行與列中的 Matrix 物件。
type: docs
url: /zh-hant/com.aspose.slides/imathmatrix/
---
**已實作介面：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

指定 Matrix 物件，其由排列在一個或多個列與欄中的子元素組成。重要的是要注意，矩陣沒有內建的分隔符。若要將矩陣放入方括號中，應使用分隔符物件 (IMathDelimiter)。可使用 null 參數在矩陣中建立空隙。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | 矩陣的元素 |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | 矩陣的元素 |
| [getRowCount()](#getRowCount--) | 矩陣的列數 |
| [getColumnCount()](#getColumnCount--) | 矩陣的欄數 |
| [getHidePlaceholders()](#getHidePlaceholders--) | 隱藏空矩陣元素的佔位符，預設：false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | 隱藏空矩陣元素的佔位符，預設：false |
| [getBaseJustification()](#getBaseJustification--) | 指定相對於周圍文字的垂直對齊方式。 |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 指定相對於周圍文字的垂直對齊方式。 |
| [getMinColumnWidth()](#getMinColumnWidth--) | 最小欄寬，以 twips 為單位 (1/20 點)。間距 (亦稱為 \\u201cColumn Gap\\u201d 或 \\u201cGap Width\\u201d) 會加到 MinColumnWidth 以決定整體矩陣欄位間距 (不同欄之相同邊緣之間的距離)。 |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | 最小欄寬，以 twips 為單位 (1/20 點)。間距 (亦稱為 \\u201cColumn Gap\\u201d 或 \\u201cGap Width\\u201d) 會加到 MinColumnWidth 以決定整體矩陣欄位間距 (不同欄之相同邊緣之間的距離)。 |
| [getColumnGapRule()](#getColumnGapRule--) | 矩陣欄位之水平間距類型；水平間距單位可以是 ems 或 points（以 twips 儲存）。 |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | 矩陣欄位之水平間距類型；水平間距單位可以是 ems 或 points（以 twips 儲存）。 |
| [getColumnGap()](#getColumnGap--) | 矩陣欄位之水平間距值；如果 ColumnGapRule 設為 3（\"Exactly\"），則單位解釋為 twips（1/20 點）；如果 ColumnGapRule 設為 4（\"Multiple\"），則單位解釋為 0.5 em 的增量數量。 |
| [setColumnGap(long value)](#setColumnGap-long-) | 矩陣欄位之水平間距值；如果 ColumnGapRule 設為 3（\"Exactly\"），則單位解釋為 twips（1/20 點）；如果 ColumnGapRule 設為 4（\"Multiple\"），則單位解釋為 0.5 em 的增量數量。 |
| [getRowGapRule()](#getRowGapRule--) | 矩陣列之垂直間距類型；垂直間距單位可以是行或 points（以 twips 儲存）。 |
| [setRowGapRule(int value)](#setRowGapRule-int-) | 矩陣列之垂直間距類型；垂直間距單位可以是行或 points（以 twips 儲存）。 |
| [getRowGap()](#getRowGap--) | 矩陣列之垂直間距值；如果 RowGapRule 設為 3（\"Exactly\"），則單位解釋為 twips（1/20 點）；如果 RowGapRule 設為 4（\"Multiple\"），則單位解釋為半行。 |
| [setRowGap(long value)](#setRowGap-long-) | 矩陣列之垂直間距值；如果 RowGapRule 設為 3（\"Exactly\"），則單位解釋為 twips（1/20 點）；如果 RowGapRule 設為 4（\"Multiple\"），則單位解釋為半行。 |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | 取得指定欄位的水平對齊方式 |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | 設定指定欄位的水平對齊方式 |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | 設定指定欄位的水平對齊方式 |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | 在指定列之前插入新列，初始時新列的所有元素皆為 null。 |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | 在指定列之後插入新列，初始時新列的所有元素皆為 null。 |
| [deleteRow(int rowIndex)](#deleteRow-int-) | 刪除指定的列 |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | 在指定欄之前插入新欄，初始時新欄的所有元素皆為 null。 |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | 在指定欄之後插入新欄，初始時新欄的所有元素皆為 null。 |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | 刪除指定的欄 |

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| row | int | 取得項目的列之零基索引 |
| column | int | 取得項目的欄之零基索引 |

**傳回值：**
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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| row | int | 取得項目的列之零基索引 |
| column | int | 取得項目的欄之零基索引 |
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

**傳回值：**
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

**傳回值：**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

隱藏空矩陣元素的佔位符，預設：false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**傳回值：**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

隱藏空矩陣元素的佔位符，預設：false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

指定相對於周圍文字的垂直對齊方式。可能的值為 top、bottom 和 center。預設：Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**傳回值：**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

指定相對於周圍文字的垂直對齊方式。可能的值為 top、bottom 和 center。預設：Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public abstract long getMinColumnWidth()
```

最小欄寬，以 twips 為單位 (1/20 點)。間距 (亦稱為 \\u201cColumn Gap\\u201d 或 \\u201cGap Width\\u201d) 會加到 MinColumnWidth 以決定整體矩陣欄位間距 (不同欄之相同邊緣之間的距離)。預設：0。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**傳回值：**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

最小欄寬，以 twips 為單位 (1/20 點)。間距 (亦稱為 \\u201cColumn Gap\\u201d 或 \\u201cGap Width\\u201d) 會加到 MinColumnWidth 以決定整體矩陣欄位間距 (不同欄之相同邊緣之間的距離)。預設：0。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public abstract int getColumnGapRule()
```

矩陣欄位之水平間距類型；水平間距單位可以是 ems 或 points（以 twips 儲存）。預設：SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**傳回值：**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```

矩陣欄位之水平間距類型；水平間距單位可以是 ems 或 points（以 twips 儲存）。預設：SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public abstract long getColumnGap()
```

矩陣欄位之水平間距值；如果 ColumnGapRule 設為 3（\"Exactly\"），則單位解釋為 twips（1/20 點）；如果 ColumnGapRule 設為 4（\"Multiple\"），則單位解釋為 0.5 em 的增量數量。其他情況將被忽略。預設：0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**傳回值：**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

矩陣欄位之水平間距值；如果 ColumnGapRule 設為 3（\"Exactly\"），則單位解釋為 twips（1/20 點）；如果 ColumnGapRule 設為 4（\"Multiple\"），則單位解釋為 0.5 em 的增量數量。其他情況將被忽略。預設：0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public abstract int getRowGapRule()
```

矩陣列之垂直間距類型；垂直間距單位可以是行或 points（以 twips 儲存）。預設：SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**傳回值：**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

矩陣列之垂直間距類型；垂直間距單位可以是行或 points（以 twips 儲存）。預設：SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public abstract long getRowGap()
```

矩陣列之垂直間距值；如果 RowGapRule 設為 3（\"Exactly\"），則單位解釋為 twips（1/20 點）；如果 RowGapRule 設為 4（\"Multiple\"），則單位解釋為半行。預設：0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**傳回值：**
long
### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```

矩陣列之垂直間距值；如果 RowGapRule 設為 3（\"Exactly\"），則單位解釋為 twips（1/20 點）；如果 RowGapRule 設為 4（\"Multiple\"），則單位解釋為半行。預設：0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**參數：**
| 參數 | 類型 | 說明 |
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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| columnIndex | int | 零基欄索引 |

**傳回值：**
int - 指定欄位的水平對齊方式
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

設定指定欄位的水平對齊方式

--------------------

> ```
> 範例:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| columnIndex | int | 零基欄索引 |
| val | int | 指定欄位水平對齊方式的新值 |

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| columnIndex | int | 第一個要設定對齊的欄之零基索引 |
| columnsCount | long | 要設定對齊的欄數量 |
| val | int | 指定欄位水平對齊方式的新值 |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

在指定列之前插入新列，初始時新列的所有元素皆為 null。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rowIndex | int | 要在其前插入新列的列索引 |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

在指定列之後插入新列，初始時新列的所有元素皆為 null。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**參數：**
| 參數 | 類型 | 說明 |
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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rowIndex | int | 要刪除的列之零基索引。 |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

在指定欄之前插入新欄，初始時新欄的所有元素皆為 null。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| columnIndex | int | 要在其前插入新欄的欄索引 |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

在指定欄之後插入新欄，初始時新欄的所有元素皆為 null。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| columnIndex | int | 要在其後插入新欄的欄索引 |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

刪除指定的欄

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| columnIndex | int | 要刪除的欄之零基索引。 |