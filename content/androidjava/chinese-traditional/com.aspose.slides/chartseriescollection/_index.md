---
title: ChartSeriesCollection
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示集合
type: docs
url: /zh-hant/com.aspose.slides/chartseriescollection/
---
**繼承自：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

表示 [ChartSeries](../../com.aspose.slides/chartseries) 的集合
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [size()](#size--) | 傳回集合中的物件數量。 |
| [add(int type)](#add-int-) | 建立新的圖表系列並將其加入集合。 |
| [insert(int index, int type)](#insert-int-int-) | 建立新的圖表系列並將其插入集合。 |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | 從 [ChartDataCell](../../com.aspose.slides/chartdatacell) 建立新的圖表系列並將其加入集合。 |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | 從 [ChartCellCollection](../../com.aspose.slides/chartcellcollection) 建立新的圖表系列並將其加入集合。 |
| [add(String name, int type)](#add-java.lang.String-int-) | 從值建立新的圖表系列並將其加入集合。 |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | 搜尋指定的 [ChartSeries](../../com.aspose.slides/chartseries)，並傳回整個 Collection 中首次出現的零基索引。 |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | 移除指定的值。 |
| [removeAt(int index)](#removeAt-int-) | 從集合中移除儲存在指定位置的 ActiveX 控制項。 |
| [clear()](#clear--) | 從集合中移除所有控制項。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將整個集合複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回一個值，指示對集合的存取是否已同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

取得指定索引處的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 指定索引處的元素。
### size() {#size--}
```
public final int size()
```

傳回集合中的物件數量。唯讀 int。

**傳回:**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

建立新的圖表系列並將其加入集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | int | 系列類型 |

**傳回:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 新圖表系列。
### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

建立新的圖表系列並將其插入集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**傳回:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

從 [ChartDataCell](../../com.aspose.slides/chartdatacell) 建立新的圖表系列並將其加入集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 包含系列名稱的儲存格。 |
| type | int | 系列的類型設定 |

--------------------

如果圖表系列已從同一儲存格建立，且該系列已在集合中，則此方法不會加入任何內容，並傳回其索引。 |

**傳回:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 已加入的圖表系列，或已存在於集合中的系列。
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

從 [ChartCellCollection](../../com.aspose.slides/chartcellcollection) 建立新的圖表系列並將其加入集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | 包含系列名稱的儲存格集合。 |
| type | int | 系列的類型設定 |

--------------------

如果圖表系列已從同一儲存格建立，且該系列已在集合中，則此方法不會加入任何內容，並傳回其索引。 |

**傳回:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 已加入的圖表系列，或已存在於集合中的系列。
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

從值建立新的圖表系列並將其加入集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 系列名稱。 |
| type | int | 系列的類型設定 |

**傳回:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 已加入的圖表系列。
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

搜尋指定的 [ChartSeries](../../com.aspose.slides/chartseries)，並傳回整個 Collection 中首次出現的零基索引。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | 圖表系列值。 |

**傳回:**
int - 指定值在整個 CollectionBase 中首次出現的零基索引（若找到）；否則為 -1。
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

移除指定的值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | 該值。 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

從集合中移除儲存在指定位置的 ActiveX 控制項。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除之控制項的索引。 |
### clear() {#clear--}
```
public final void clear()
```

從集合中移除所有控制項。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

傳回可遍歷集合的列舉器。

**傳回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - 整個集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將整個集合複製到指定的陣列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列 |
| index | int | 目標陣列中的索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回一個值，指示對集合的存取是否已同步（執行緒安全）。唯讀 boolean。
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。