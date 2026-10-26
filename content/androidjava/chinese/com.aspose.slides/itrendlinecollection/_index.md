---
title: ITrendlineCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 TrendlineEx 的集合
type: docs
url: /zh/com.aspose.slides/itrendlinecollection/
---
**所有已实现的接口:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

表示 TrendlineEx 的集合
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [getCount()](#getCount--) | 获取集合中实际包含的元素数量。 |
| [add(int trendlineType)](#add-int-) | 在集合末尾添加新的 Trendline 并返回它。 |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | 移除指定的值。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```


获取指定索引处的元素。只读 [ITrendline](../../com.aspose.slides/itrendline)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```


获取集合中实际包含的元素数量。只读 int。

**返回值:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```


在集合末尾添加新的 Trendline 并返回它。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| trendlineType | int | Trendline 类型 [TrendlineType](../../com.aspose.slides/trendlinetype) |

**返回值:**
[ITrendline](../../com.aspose.slides/itrendline) - 新的 Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```


移除指定的值。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | 要移除的 Trendline [ITrendline](../../com.aspose.slides/itrendline) |