---
title: ChartCategoryCollection
second_title: Aspose.Slides for Android Java API 參考
description: 表示集合
type: docs
url: /zh-hant/com.aspose.slides/chartcategorycollection/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**已實作的所有介面：**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

代表 [ChartCategory](../../com.aspose.slides/chartcategory) 的集合
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [getUseCells()](#getUseCells--) | 如果為 true，則工作表用於儲存類別（此情況支援多層類別）。 |
| [setUseCells(boolean value)](#setUseCells-boolean-) | 如果為 true，則工作表用於儲存類別（此情況支援多層類別）。 |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | 回傳已使用的類別分組層級數量。 |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | 如果集合中已存在類別，則回傳該類別。 |
| [add(Object value)](#add-java.lang.Object-) | 從值建立新的 [ChartCategory](../../com.aspose.slides/chartcategory) 並將其加入集合。 |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | 搜尋指定的 [ChartCategory](../../com.aspose.slides/chartcategory)，並回傳在整個 Collection 中首次出現的零基索引。 |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | 移除指定的值。 |
| [removeAt(int index)](#removeAt-int-) | 移除給定索引處的元素。 |
| [clear()](#clear--) | 移除集合中的所有元素。 |
| [iterator()](#iterator--) | 回傳用於遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 回傳整個集合的 java 迭代器。 |
| [size()](#size--) | 回傳集合中元素的數量。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 回傳一個值，指出對 List 的存取是否已同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 回傳一個可用於同步存取集合的物件。 |
### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

取得指定索引處的元素。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int |  |

**回傳：**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 指定索引處的元素。

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

如果為 true，則工作表用於儲存類別（此情況支援多層類別）。如果為 false，則工作表不會用於儲存值（此情況不支援多層類別）。讀/寫布林值。

**回傳：**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

如果為 true，則工作表用於儲存類別（此情況支援多層類別）。如果為 false，則工作表不會用於儲存值（此情況不支援多層類別）。讀/寫布林值。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

回傳已使用的類別分組層級數量。對於多層類別而言，數量大於一。唯讀 int。

**回傳：**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

如果集合中已存在類別，則回傳它。否則從 [IChartDataCell](../../com.aspose.slides/ichartdatacell) 建立新的圖表類別並將其加入集合。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 用於建立圖表類別的儲存格。 |

**回傳：**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 已加入或已存在的類別。

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

從值建立新的 [ChartCategory](../../com.aspose.slides/chartcategory) 並將其加入集合。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.Object | 值。 |

--------------------

此方法會新增名稱為 AUTO_DATA 的工作表，並將所有值加入其中。如果您使用 [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) 來新增或編輯儲存格值，請確保不要使用此工作表。使用此方法新增的值的最大數量不得超過 16711680。

**回傳：**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 已加入的 [IChartCategory](../../com.aspose.slides/ichartcategory)。

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

搜尋指定的 [ChartCategory](../../com.aspose.slides/chartcategory)，並回傳在整個 Collection 中首次出現的零基索引。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | 圖表類別。 |

**回傳：**
int - 若在整個 CollectionBase 中找到值，則回傳其零基索引；若未找到，則回傳 -1。

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

移除指定的值。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | 值。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除給定索引處的元素。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 要移除之類別的索引。 |

### clear() {#clear--}
```
public final void clear()
```

移除集合中的所有元素。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

回傳用於遍歷集合的列舉器。

**回傳：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

回傳整個集合的 java 迭代器。

**回傳：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - 整個集合的 java.util.Iterator。

### size() {#size--}
```
public final int size()
```

回傳集合中元素的數量。唯讀 int。

**回傳：**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 陣列中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

回傳一個值，指出對 List 的存取是否已同步（執行緒安全）。唯讀布林值。

**回傳：**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

回傳一個可用於同步存取集合的物件。唯讀 Object。  
回傳同步根物件。唯讀 Object。

**回傳：**
java.lang.Object