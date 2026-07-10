---
title: SectionSlideCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示节中的幻灯片集合。
type: docs
url: /zh/com.aspose.slides/sectionslidecollection/
---
**继承:**  
java.lang.Object, com.aspose.slides.DomObject

**所有已实现的接口:**  
[com.aspose.slides.ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)  
```
public final class SectionSlideCollection extends DomObject<Section> implements ISectionSlideCollection
```

表示节中的幻灯片集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [size()](#size--) | 获取集合实际包含的元素数量。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将整个集合复制到指定的数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否已同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

获取指定索引处的元素。只读 [ISlide](../../com.aspose.slides/islide)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[ISlide](../../com.aspose.slides/islide)

### size() {#size--}
```
public final int size()
```

获取集合实际包含的元素数量。只读 int。

**返回值:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将整个集合复制到指定的数组。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组 |
| index | int | 目标数组中的索引。 |

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

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

返回遍历集合的枚举器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - 一个可以用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - 一个用于整个集合的 java.util.Iterator。