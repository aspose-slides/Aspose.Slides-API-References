---
title: AdjustValueCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示形状调整的集合。
type: docs
url: /zh/com.aspose.slides/adjustvaluecollection/
---
**继承:**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口:**
[com.aspose.slides.IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
```
public final class AdjustValueCollection extends DomObject<GeometryShape> implements IAdjustValueCollection
```

表示形状的调整集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 返回调整的数量。 |
| [get_Item(int index)](#get-Item-int-) | 根据索引返回调整。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否已同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根对象。 |
| [iterator()](#iterator--) | 返回整个集合的枚举器。 |
### size() {#size--}
```
public final int size()
```

返回调整的数量。只读 int。

**返回:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAdjustValue get_Item(int index)
```

根据索引返回调整。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 调整的索引。 |

**返回:**
[IAdjustValue](../../com.aspose.slides/iadjustvalue) - [AdjustValue](../../com.aspose.slides/adjustvalue).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将集合中的所有元素复制到指定数组。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 目标数组中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一个值，指示对集合的访问是否已同步（线程安全）。只读 boolean。

**返回:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根对象。只读 Object。

**返回:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.IEnumerator iterator()
```

返回整个集合的枚举器。

**返回:**
com.aspose.ms.System.Collections.IEnumerator