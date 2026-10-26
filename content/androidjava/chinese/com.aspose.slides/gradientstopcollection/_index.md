---
title: GradientStopCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一组渐变停止点的集合。
type: docs
url: /zh/com.aspose.slides/gradientstopcollection/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**全部已实现的接口：**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

表示一组渐变停止点的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | 返回集合中渐变停止点的数量。 |
| [get_Item(int index)](#get-Item-int-) | 按索引返回渐变停止点。 |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | 创建新的渐变停止点并将其添加到集合的末尾。 |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | 创建新的渐变停止点并将其添加到集合的末尾。 |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | 创建新的渐变停止点并将其添加到集合的末尾。 |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | 创建新的渐变停止点并将其插入到集合中指定的索引位置。 |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | 创建新的渐变停止点并将其插入到集合中指定的索引位置。 |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | 创建新的渐变停止点并将其插入到集合中指定的索引位置。 |
| [removeAt(int index)](#removeAt-int-) | 删除指定索引处的渐变停止点。 |
| [clear()](#clear--) | 从集合中删除所有渐变停止点。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定的数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否已同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```


版本。只读 long。

**返回：**
long
### size() {#size--}
```
public final int size()
```


返回集合中渐变停止点的数量。只读 int 。

**返回：**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```


按索引返回渐变停止点。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```


创建新的渐变停止点并将其添加到集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | float | 新渐变停止点的位置。 |
| color | java.lang.Integer | 新渐变停止点的颜色。 |

**返回：**
[IGradientStop](../../com.aspose.slides/igradientstop) - 集合中新渐变停止点的索引。
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```


创建新的渐变停止点并将其添加到集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | float | 新渐变停止点的位置。 |
| presetColor | int | 新渐变停止点的颜色。 |

**返回：**
[IGradientStop](../../com.aspose.slides/igradientstop) - 集合中新渐变停止点的索引。
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```


创建新的渐变停止点并将其添加到集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | float | 新渐变停止点的位置。 |
| schemeColor | int | 新渐变停止点的颜色。 |

**返回：**
[IGradientStop](../../com.aspose.slides/igradientstop) - 集合中新渐变停止点的索引。
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```


创建新的渐变停止点并将其插入到集合中指定的索引位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在集合中要插入新渐变停止点的索引。 |
| position | float | 新渐变停止点的位置。 |
| color | java.lang.Integer | 新渐变停止点的颜色。 |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```


创建新的渐变停止点并将其插入到集合中指定的索引位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在集合中要插入新渐变停止点的索引。 |
| position | float | 新渐变停止点的位置。 |
| presetColor | int | 新渐变停止点的颜色。 |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```


创建新的渐变停止点并将其插入到集合中指定的索引位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在集合中要插入新渐变停止点的索引。 |
| position | float | 新渐变停止点的位置。 |
| schemeColor | int | 新渐变停止点的颜色。 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


删除指定索引处的渐变停止点。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应删除的渐变停止点的索引。 |
### clear() {#clear--}
```
public final void clear()
```


从集合中删除所有渐变停止点。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```


返回遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```


返回整个集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - 整个集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


将集合中的所有元素复制到指定的数组。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 目标数组中的起始索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


返回一个值，指示对集合的访问是否已同步（线程安全）。只读 boolean 。

**返回：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


返回同步根。只读 Object。

**返回：**
java.lang.Object