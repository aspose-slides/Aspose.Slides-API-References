---
title: ITrendlineCollection
second_title: Aspose.Slides for Java API 參考文件
description: 表示 TrendlineEx 的集合
type: docs
url: /zh-hant/com.aspose.slides/itrendlinecollection/
---
**所有實作的介面：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

表示 TrendlineEx 的集合
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [getCount()](#getCount--) | 取得集合實際包含的元素數量。 |
| [add(int trendlineType)](#add-int-) | 在集合末尾加入新的 Trendline 並傳回它。 |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | 移除指定的值。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```


取得指定索引處的元素。唯讀 [ITrendline](../../com.aspose.slides/itrendline)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```


取得集合實際包含的元素數量。唯讀 int。

**返回值:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```


在集合末尾加入新的 Trendline 並傳回它。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| trendlineType | int | 趨勢線類型 [TrendlineType](../../com.aspose.slides/trendlinetype) |

**返回值:**
[ITrendline](../../com.aspose.slides/itrendline) - 新的 Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```


移除指定的值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | 要移除的 Trendline [ITrendline](../../com.aspose.slides/itrendline) |