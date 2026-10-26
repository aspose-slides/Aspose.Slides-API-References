---
title: MathMatrix
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 指定由子元素排列成一或多列與欄的矩陣物件。
type: docs
url: /zh-hant/com.aspose.slides/mathmatrix/
---
**繼承關係：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**已實作介面：**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

指定矩陣物件，由一或多列與欄中的子元素排列組成。需要注意的是，矩陣沒有內建的分隔符。若要將矩陣放入括號中，應使用分隔符物件 (IMathDelimiter)。可使用空值參數在矩陣中建立空格。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## 建構函式

| 建構式 | 說明 |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | 初始化 MathMatrix 類別的新執行個體。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getRowCount()](#getRowCount--) | 矩陣的列數 |
| [getColumnCount()](#getColumnCount--) | 矩陣的欄數 |
| [getHidePlaceholders()](#getHidePlaceholders--) | 隱藏空矩陣元素的佔位符。預設：false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | 隱藏空矩陣元素的佔位符。預設：false |
| [getBaseJustification()](#getBaseJustification--) | 指定相對於周圍文字的垂直對齊方式。 |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 指定相對於周圍文字的垂直對齊方式。 |
| [getMinColumnWidth()](#getMinColumnWidth--) | 以 twips（1/20 點）為單位的最小欄寬。間距（亦稱「Column Gap」或「Gap Width」）會加到 MinColumnWidth，以決定整體矩陣欄距（不同欄的相同邊緣之間的距離）。 |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | 以 twips（1/20 點）為單位的最小欄寬。間距（亦稱「Column Gap」或「Gap Width」）會加到 MinColumnWidth，以決定整體矩陣欄距（不同欄的相同邊緣之間的距離）。 |
| [getColumnGapRule()](#getColumnGapRule--) | 矩陣欄之間的水平間距類型；水平間距單位可以是 ems 或 points（以 twips 儲存）。 |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | 矩陣欄之間的水平間距類型；水平間距單位可以是 ems 或 points（以 twips 儲存）。 |
| [getColumnGap()](#getColumnGap--) | 矩陣欄之間的水平間距值；若 ColumnGapRule 設為 3（「Exactly」），則單位解讀為 twips（1/20 點）；若設定為 4（「Multiple」），則單位解讀為 0.5 em 的增量數。 |
| [setColumnGap(long value)](#setColumnGap-long-) | 矩陣欄之間的水平間距值；若 ColumnGapRule 設為 3（「Exactly」），則單位解讀為 twips（1/20 點）；若設定為 4（「Multiple」），則單位解讀為 0.5 em 的增量數。 |
| [getRowGapRule()](#getRowGapRule--) | 矩陣列之間的垂直間距類型；垂直間距單位可以是 lines 或 points（以 twips 儲存）。 |
| [setRowGapRule(int value)](#setRowGapRule-int-) | 矩陣列之間的垂直間距類型；垂直間距單位可以是 lines 或 points（以 twips 儲存）。 |
| [getRowGap()](#getRowGap--) | 矩陣列之間的垂直間距值；若 RowGapRule 設為 3（「Exactly」），則單位解讀為 twips（1/20 點）；若設定為 4（「Multiple」），則單位解讀為半行。 |
| [setRowGap(long value)](#setRowGap-long-) | 矩陣列之間的垂直間距值；若 RowGapRule 設為 3（「Exactly」），則單位解讀為 twips（1/20 點）；若設定為 4（「Multiple」），則單位解讀為半行。 |
| [get_Item(int row, int column)](#get-Item-int-int-) | 矩陣元素 |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | 矩陣元素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 控制字元屬性 |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | 取得指定欄的水平對齊方式 |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | 設定指定欄的水平對齊方式 |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | 設定指定欄的水平對齊方式 |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | 在指定列之前插入新列；新列中的所有元素皆為 null。 |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | 在指定列之後插入新列；新列中的所有元素皆為 null。 |
| [deleteRow(int rowIndex)](#deleteRow-int-) | 刪除指定的列 |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | 在指定欄之前插入新欄；新欄中的所有元素皆為 null。 |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | 在指定欄之後插入新欄；新欄中的所有元素皆為 null。 |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | 刪除指定的欄 |
| [getChildren()](#getChildren--) | 取得子元素 |
### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

初始化 MathMatrix 類別的新執行個體。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| rowCount | int | 列數 |
| columnCount | int | 欄數 |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
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
public final int getColumnCount()
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
public final boolean getHidePlaceholders()
```

隱藏空矩陣元素的佔位符。預設：false

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
public final void setHidePlaceholders(boolean value)
```

隱藏空矩陣元素的佔位符。預設：false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

指定相對於周圍文字的垂直對齊方式。可能的值有 top、bottom 和 center。預設：Center

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
public final void setBaseJustification(int value)
```

指定相對於周圍文字的垂直對齊方式。可能的值有 top、bottom 和 center。預設：Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```

以 twips（1/20 點）為單位的最小欄寬。間距（亦稱「Column Gap」或「Gap Width」）會加到 MinColumnWidth，以決定整體矩陣欄距（不同欄的相同邊緣之間的距離）。預設：0。

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
public final void setMinColumnWidth(long value)
```

以 twips（1/20 點）為單位的最小欄寬。間距（亦稱「Column Gap」或「Gap Width」）會加到 MinColumnWidth，以決定整體矩陣欄距（不同欄的相同邊緣之間的距離）。預設：0。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public final int getColumnGapRule()
```

矩陣欄之間的水平間距類型；水平間距單位可以是 ems 或 points（以 twips 儲存）。預設：SingleSpacingGap (0)

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
public final void setColumnGapRule(int value)
```

矩陣欄之間的水平間距類型；水平間距單位可以是 ems 或 points（以 twips 儲存）。預設：SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```

矩陣欄之間的水平間距值；若 ColumnGapRule 設為 3（「Exactly」），則單位解讀為 twips（1/20 點）；若設定為 4（「Multiple」），則單位解讀為 0.5 em 的增量數。其他情況下忽略。預設：0

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
public final void setColumnGap(long value)
```

矩陣欄之間的水平間距值；若 ColumnGapRule 設為 3（「Exactly」），則單位解讀為 twips（1/20 點）；若設定為 4（「Multiple」），則單位解讀為 0.5 em 的增量數。其他情況下忽略。預設：0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public final int getRowGapRule()
```

矩陣列之間的垂直間距類型；垂直間距單位可以是 lines 或 points（以 twips 儲存）。預設：SingleSpacingGap (0)

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
public final void setRowGapRule(int value)
```

矩陣列之間的垂直間距類型；垂直間距單位可以是 lines 或 points（以 twips 儲存）。預設：SingleSpacingGap (0)

--------------------

> ```
> 範例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public final long getRowGap()
```

矩陣列之間的垂直間距值；若 RowGapRule 設為 3（「Exactly」），則單位解讀為 twips（1/20 點）；若設定為 4（「Multiple」），則單位解讀為半行。其他情況下忽略。預設：0

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
public final void setRowGap(long value)
```

矩陣列之間的垂直間距值；若 RowGapRule 設為 3（「Exactly」），則單位解讀為 twips（1/20 點）；若設定為 4（「Multiple」），則單位解讀為半行。其他情況下忽略。預設：0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | long |  |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

矩陣元素

--------------------

> ```
> 範例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| row | int | 要取得項目的列之零基索引 |
| column | int | 要取得項目的欄之零基索引 |

**傳回值：**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

矩陣元素

--------------------

> ```
> 範例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| row | int | 要取得項目的列之零基索引 |
| column | int | 要取得項目的欄之零基索引 |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

控制字元屬性

**傳回值：**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

取得指定欄的水平對齊方式

--------------------

> ```
> 範例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| columnIndex | int | 零基欄索引 |

**傳回值：**
int - 指定欄的水平對齊方式
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

設定指定欄的水平對齊方式

--------------------

> ```
> 範例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| columnIndex | int | 零基欄索引 |
| val | int | 指定欄的水平對齊方式新值 |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

設定指定欄的水平對齊方式

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| columnIndex | int | 要設定對齊方式的第一個欄的零基索引 |
| columnsCount | long | 要設定對齊方式的欄數 |
| val | int | 指定欄的水平對齊方式新值 |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

在指定列之前插入新列；新列中的所有元素皆為 null。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| rowIndex | int | 要在其前插入新列的列索引 |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

在指定列之後插入新列；新列中的所有元素皆為 null。

--------------------

> ```
> 範例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| rowIndex | int | 要在其後插入新列的列索引 |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

刪除指定的列

--------------------

> ```
> 範例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| rowIndex | int | 要刪除之列的零基索引。 |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

在指定欄之前插入新欄；新欄中的所有元素皆為 null。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| columnIndex | int | 要在其前插入新欄的欄索引 |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

在指定欄之後插入新欄；新欄中的所有元素皆為 null。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| columnIndex | int | 要在其後插入新欄的欄索引 |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
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
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| columnIndex | int | 要刪除之欄的零基索引。 |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

取得子元素

**傳回值：**
com.aspose.slides.IMathElement[]