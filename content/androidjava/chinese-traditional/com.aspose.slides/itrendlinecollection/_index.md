---
title: ITrendlineCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示 TrendlineEx 的集合
type: docs
url: /zh-hant/com.aspose.slides/itrendlinecollection/
---
**所有已實作的介面:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable  
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

表示 TrendlineEx 的集合
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [getCount()](#getCount--) | 取得集合中實際包含的元素數量。 |
| [add(int trendlineType)](#add-int-) | 在集合末端新增趨勢線並回傳它。 |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | 移除指定的值。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```

取得指定索引處的元素。唯讀 [ITrendline](../../com.aspose.slides/itrendline)。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int |  |

**傳回值:**  
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```

取得集合中實際包含的元素數量。唯讀 int。

**傳回值:**  
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```

在集合末端新增趨勢線並回傳它。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| trendlineType | int | 趨勢線類型 [TrendlineType](../../com.aspose.slides/trendlinetype) |

**傳回值:**  
[ITrendline](../../com.aspose.slides/itrendline) - 新趨勢線 [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```

移除指定的值。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | 要移除的趨勢線 [ITrendline](../../com.aspose.slides/itrendline) |