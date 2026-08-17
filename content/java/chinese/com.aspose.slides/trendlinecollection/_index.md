---
title: TrendlineCollection
second_title: Aspose.Slides for Java API 参考
description: 表示 Trendline 的集合
type: docs
url: /zh/com.aspose.slides/trendlinecollection/
---
**继承:**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口:**
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

表示 Trendline 的集合
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [add(int trendlineType)](#add-int-) | 在集合末尾添加新的 Trendline 并返回它。 |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | 移除指定的值。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [getCount()](#getCount--) | 获取集合实际包含的元素数量。 |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

获取指定索引处的元素。只读 [Trendline](../../com.aspose.slides/trendline)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```

在集合末尾添加新的 Trendline 并返回它。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| trendlineType | int |  |

**返回:**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```

移除指定的值。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```

返回一个遍历集合的枚举器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - An java.util.Iterator for the entire collection.
### getCount() {#getCount--}
```
public final int getCount()
```

获取集合实际包含的元素数量。只读 int。

**返回:**
int