---
title: MathMatrix
second_title: Aspose.Slides for Java API 參考
description: 指定矩陣物件，由子元素以一或多列與多行排列組成。
type: docs
url: /zh-hant/com.aspose.slides/mathmatrix/
---
**繼承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**已實作的所有介面：**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

指定矩陣物件，由子元素以一或多列與多行排列組成。需要注意的是，矩陣沒有內建的分隔符。若要將矩陣放入括號中，應使用分隔符物件 (IMathDelimiter)。可使用 null 參數在矩陣中建立空隙。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## 建構子

| 建構子 | 說明 |
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
| [getMinColumnWidth()](#getMinColumnWidth--) | 最小欄寬，以 twips（點的 1/20）為單位。間距（亦稱「Column Gap」或「Gap Width」）會加到 MinColumnWidth 以決定整體矩陣欄間距（不同欄之相同邊緣之間的距離）。 |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | 最小欄寬，以 twips（點的 1/20）為單位。間距（亦稱「Column Gap」或「Gap Width」）會加到 MinColumnWidth 以決定整體矩陣欄間距（不同欄之相同邊緣之間的距離）。 |
| [getColumnGapRule()](#getColumnGapRule--) | 矩陣欄之水平間距類型；水平間距單位可以是 em 或點（以 twips 儲存）。 |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | 矩陣欄之水平間距類型；水平間距單位可以是 em 或點（以 twips 儲存）。 |
| [getColumnGap()](#getColumnGap--) | 矩陣欄之水平間距值；若 ColumnGapRule 設為 3（「Exactly」），則單位解讀為 twips（點的 1/20）；若設為 4（「Multiple」），則單位解讀為 0.5 em 的倍數。 |
| [setColumnGap(long value)](#setColumnGap-long-) | 矩陣欄之水平間距值；若 ColumnGapRule 設為 3（「Exactly」），則單位解讀為 twips（點的 1/20）；若設為 4（「Multiple」），則單位解讀為 0.5 em 的倍數。 |
| [getRowGapRule()](#getRowGapRule--) | 矩陣列之垂直間距類型；垂直間距單位可以是行或點（以 twips 儲存）。 |
| [setRowGapRule(int value)](#setRowGapRule-int-) | 矩陣列之垂直間距類型；垂直間距單位可以是行或點（以 twips 儲存）。 |
| [getRowGap()](#getRowGap--) | 矩陣列之垂直間距值；若 RowGapRule 設為 3（「Exactly」），則單位解讀為 twips（點的 1/20）；若設為 4（「Multiple」），則單位解讀為半行。 |
| [setRowGap(long value)](#setRowGap-long-) | 矩陣列之垂直間距值；若 RowGapRule 設為 3（「Exactly」），則單位解讀為 twips（點的 1/20）；若設為 4（「Multiple」），則單位解讀為半行。 |
| [get_Item(int row, int column)](#get-Item-int-int-) | 矩陣元素 |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | 矩陣元素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 控制字元屬性 |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | 取得指定欄的水平對齊方式 |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | 設定指定欄的水平對齊方式 |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | 設定指定欄的水平對齊方式 |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | 在指定位置之前插入新行，該新行的所有元素初始為 null。 |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | 在指定位置之後插入新行，該新行的所有元素初始為 null。 |
| [deleteRow(int rowIndex)](#deleteRow-int-) | 刪除指定的列 |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | 在指定位置之前插入新欄，該新欄的所有元素初始為 null。 |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | 在指定位置之後插入新欄，該新欄的所有元素初始為 null。 |
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
| 參數 | 類型 | 說明 |
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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
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
public final void setBaseJustification(int value)
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
public final long getMinColumnWidth()
```

最小欄寬，以 twips（點的 1/20）為單位。間距（亦稱「Column Gap」或「Gap Width」）會加到 MinColumnWidth 以決定整體矩陣欄間距（不同欄之相同邊緣之間的距離）。預設：0.

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

最小欄寬，以 twips（點的 1/20）為單位。間距（亦稱「Column Gap」或「Gap Width」）會加到 MinColumnWidth 以決定整體矩陣欄間距（不同欄之相同邊緣之間的距離）。預設：0.

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
public final int getColumnGapRule()
```

矩陣欄之水平間距類型；水平間距單位可以是 em 或點（以 twips 儲存）。預設：SingleSpacingGap (0)

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

矩陣欄之水平間距類型；水平間距單位可以是 em 或點（以 twips 儲存）。預設：SingleSpacingGap (0)

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
public final long getColumnGap()
```

矩陣欄之水平間距值；若 ColumnGapRule 設為 3（「Exactly」），則單位解讀為 twips（點的 1/20）；若設為 4（「Multiple」），則單位解讀為 0.5 em 的倍數。在其他情況下忽略。預設：0

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

矩陣欄之水平間距值；若 ColumnGapRule 設為 3（「Exactly」），則單位解讀為 twips（點的 1/20）；若設為 4（「Multiple」），則單位解讀為 0.5 em 的倍數。在其他情況下忽略。預設：0

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
public final int getRowGapRule()
```

矩陣列之垂直間距類型；垂直間距單位可以是行或點（以 twips 儲存）。預設：SingleSpacingGap (0)

--------------------

> ```
> 範例:
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

矩陣列之垂直間距類型；垂直間距單位可以是行或點（以 twips 儲存）。預設：SingleSpacingGap (0)

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
public final long getRowGap()
```

矩陣列之垂直間距值；若 RowGapRule 設為 3（「Exactly」），則單位解讀為 twips（點的 1/20）；若設為 4（「Multiple」），則單位解讀為半行。預設：0

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

矩陣列之垂直間距值；若 RowGapRule 設為 3（「Exactly」），則單位解讀為 twips（點的 1/20）；若設為 4（「Multiple」），則單位解讀為半行。預設：0

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

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

矩陣元素

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
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**參數：**
| 參數 | 類型 | 說明 |
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
int - 指定欄的水平對齊方式
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

設定指定欄的水平對齊方式

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| columnIndex | int | 零基欄索引 |
| val | int | 指定欄的水平對齊方式的新值 |

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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| columnIndex | int | 第一個要設定對齊方式的欄之零基索引 |
| columnsCount | long | 要指定對齊方式的欄數 |
| val | int | 指定欄的水平對齊方式的新值 |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

在指定位置之前插入新行，該新行的所有元素初始為 null。

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
| rowIndex | int | 要在其前插入新行的列索引 |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

在指定位置之後插入新行，該新行的所有元素初始為 null。

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
| rowIndex | int | 要在其後插入新行的列索引 |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
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
public final void insertColumnBefore(int columnIndex)
```

在指定位置之前插入新欄，該新欄的所有元素初始為 null。

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
public final void insertColumnAfter(int columnIndex)
```

在指定位置之後插入新欄，該新欄的所有元素初始為 null。

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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| columnIndex | int | 要刪除的欄之零基索引。 |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

取得子元素

**傳回值：**
com.aspose.slides.IMathElement[]