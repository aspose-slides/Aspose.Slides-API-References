---
title: ChartCategoryCollection
second_title: Aspose.Slides for Java API 參考
description: 表示...的集合
type: docs
url: /zh-hant/com.aspose.slides/chartcategorycollection/
---
**繼承:**  
java.lang.Object, com.aspose.slides.DomObject

**全部已實作的介面:**  
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)  
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

表示 [ChartCategory](../../com.aspose.slides/chartcategory) 的集合  
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [getUseCells()](#getUseCells--) | 如果為 true，則工作表用於儲存類別（此情況支援多層類別）。 |
| [setUseCells(boolean value)](#setUseCells-boolean-) | 如果為 true，則工作表用於儲存類別（此情況支援多層類別）。 |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | 傳回使用的類別分組層級數。 |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | 如果集合中已存在類別，則傳回該類別。 |
| [add(Object value)](#add-java.lang.Object-) | 從值建立新的 [ChartCategory](../../com.aspose.slides/chartcategory) 並將其加入集合。 |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | 搜尋指定的 [ChartCategory](../../com.aspose.slides/chartcategory)，並傳回整個集合中首次出現的零基索引。 |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | 移除指定的值。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的元素。 |
| [clear()](#clear--) | 從集合中移除所有元素。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉子。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [size()](#size--) | 傳回集合中的元素數量。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回一個值，表示對 List 的存取是否已同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回一個可用於同步存取集合的物件。 |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

取得指定索引處的元素。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值:**  
[IChartCategory](../../com.aspose.slides/ichartcategory) - 指定索引處的元素。

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

如果為 true，則工作表用於儲存類別（此情況支援多層類別）。如果為 false，則工作表不會用於儲存值（且此情況不支援多層類別）。讀寫布林值。

**傳回值:**  
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

如果為 true，則工作表用於儲存類別（此情況支援多層類別）。如果為 false，則工作表不會用於儲存值（且此情況不支援多層類別）。讀寫布林值。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

傳回使用的類別分組層級數。對於多層類別，此值大於一。唯讀 int。

**傳回值:**  
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

如果集合中已存在類別，則傳回該類別。否則從 [IChartDataCell](../../com.aspose.slides/ichartdatacell) 建立新的圖表類別並將其加入集合。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 用於建立圖表類別的儲存格。 |

**傳回值:**  
[IChartCategory](../../com.aspose.slides/ichartcategory) - 已新增或已存在的類別。

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

從值建立新的 [ChartCategory](../../com.aspose.slides/chartcategory) 並將其加入集合。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.Object | 值。 |

--------------------

此方法會新增名稱為 AUTO_DATA 的工作表，並將所有值加入其中。若使用 [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) 來新增或編輯儲存格值，請確保不要使用此工作表。使用此方法新增的值的最大數量不得超過 16711680 |

**傳回值:**  
[IChartCategory](../../com.aspose.slides/ichartcategory) - 已新增 [IChartCategory](../../com.aspose.slides/ichartcategory)。

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

搜尋指定的 [ChartCategory](../../com.aspose.slides/chartcategory)，並傳回整個集合中首次出現的零基索引。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | 圖表類別。 |

**傳回值:**  
int - 若找到，傳回整個 CollectionBase 中值首次出現的零基索引；若未找到，傳回 -1。

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

移除指定的值。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | 值。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除給定索引處的元素。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除之類別的索引。 |

### clear() {#clear--}
```
public final void clear()
```

從集合中移除所有元素。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

傳回可遍歷集合的列舉子。

**傳回值:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回值:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - java.util.Iterator 用於整個集合。

### size() {#size--}
```
public final int size()
```

傳回集合中的元素數量。唯讀 int。

**傳回值:**  
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 陣列中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回一個值，表示對 List 的存取是否已同步（執行緒安全）。唯讀布林值。

**傳回值:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回一個可用於同步存取集合的物件。唯讀 Object。  
傳回同步根。唯讀 Object。

**傳回值:**  
java.lang.Object