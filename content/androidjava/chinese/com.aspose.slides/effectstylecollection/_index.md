---
title: EffectStyleCollection
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示一个效果样式的集合。
type: docs
url: /zh/com.aspose.slides/effectstylecollection/
---
**继承:**
java.lang.Object, com.aspose.slides.DomObject

**所有已实现的接口:**
[com.aspose.slides.IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection)
```
public final class EffectStyleCollection extends DomObject<FormatScheme> implements IEffectStyleCollection
```

表示一个效果样式的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定位置的元素。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [size()](#size--) | 返回集合中元素的数量。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否已同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |

### get_Item(int index) {#get-Item-int-}
```
public final IEffectStyle get_Item(int index)
```

返回指定位置的元素。只读 [EffectStyle](../../com.aspose.slides/effectstyle)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 元素的位置。 |

**返回值:**
[IEffectStyle](../../com.aspose.slides/ieffectstyle) - 指定位置的元素。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iterator()
```

返回遍历集合的枚举器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - 一个可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - 一个用于整个集合的 java.util.Iterator。

### size() {#size--}
```
public final int size()
```

返回集合中元素的数量。只读 int， 只读 int。

**返回值:**
int

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

**返回值:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object。

**返回值:**
java.lang.Object