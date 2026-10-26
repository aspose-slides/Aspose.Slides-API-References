---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides for Android 之 Java API 參考
description: 表示一個點集合，用於在條形餅圖或餅形餅圖中以自訂切割點進行分割。
type: docs
url: /zh-hant/com.aspose.slides/piesplitcustompointcollection/
---
**繼承:**  
java.lang.Object

**已實作的介面:**  
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)  
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

表示一個點集合，用於在條形餅圖或餅形餅圖中以自訂切割點進行分割。  
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 傳回指定索引的圖表資料點。 |
| [add(int dataPointIndex)](#add-int-) | 依其在父系列點集合中的索引新增資料點。 |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | 將資料點加入集合。 |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | 從集合中移除項目。 |
| [remove(int dataPointIndex)](#remove-int-) | 依其在父系列點集合中的索引從集合中移除項目。 |
| [clear()](#clear--) | 從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除所有項目。 |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | 判斷 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | 將 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素複製到陣列，從特定的陣列索引開始。 |
| [size()](#size--) | 傳回或設定圖表資料點的計數。 |
| [isReadOnly()](#isReadOnly--) | 取得指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否唯讀的值。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示集合的存取是否同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

傳回指定索引的圖表資料點。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 索引。 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 圖表資料點。
### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

依其在父系列點集合中的索引新增資料點。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dataPointIndex | int | 父系列點集合中資料點的索引。 |
### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

將資料點加入集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 要加入的資料點。 |
### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

從集合中移除項目。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 要移除的資料點。 |

**傳回值:**
boolean - 若項目成功移除則為 true；否則為 false。如果在 System.Collections.Generic.List{T} 中找不到項目，該方法亦會傳回 false。
### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

依其在父系列點集合中的索引從集合中移除項目。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dataPointIndex | int | 父系列點集合中資料點的索引。 |
### clear() {#clear--}
```
public final void clear()
```

從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除所有項目。
### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

判斷 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的物件。 |

**傳回值:**
boolean - 若在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到項目則為 true；否則為 false。
### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

將 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素複製到陣列，從特定的陣列索引開始。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | 作為元素複製目標的一維陣列，從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 複製過來。該陣列必須使用零基索引。 |
| arrayIndex | int | 在陣列中開始複製的零基索引。 |
### size() {#size--}
```
public final int size()
```

傳回或設定圖表資料點的計數。唯讀 int。

**傳回值:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

取得指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否唯讀的值。唯讀布林值。

**傳回值:**
boolean - 若 [IGenericCollection](../../com.aspose.slides/igenericcollection) 為唯讀則為 true；否則為 false。
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回指示集合的存取是否同步（執行緒安全）的值。唯讀布林值。

**傳回值:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**傳回值:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

傳回可遍歷集合的列舉器。

**傳回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - 整個集合的 java.util.Iterator。