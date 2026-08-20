---
title: TrendlineCollection
second_title: Aspose.Slides for Java API 參考
description: 表示 Trendline 的集合
type: docs
url: /zh-hant/com.aspose.slides/trendlinecollection/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

表示 Trendline 的集合
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [add(int trendlineType)](#add-int-) | 在集合的末端新增 Trendline 並傳回它。 |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | 移除指定的值。 |
| [iterator()](#iterator--) | 傳回用於遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [getCount()](#getCount--) | 取得集合實際包含的元素數量。 |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

取得指定索引處的元素。唯讀 [Trendline](../../com.aspose.slides/trendline)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值：**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```

在集合的末端新增 Trendline 並傳回它。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| trendlineType | int |  |

**傳回值：**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```

移除指定的值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```

傳回用於遍歷集合的列舉器。

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - 整個集合的 java.util.Iterator。

### getCount() {#getCount--}
```
public final int getCount()
```

取得集合實際包含的元素數量。唯讀 int。

**傳回值：**
int