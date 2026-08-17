---
title: VbaReferenceCollection
second_title: Aspose.Slides Java API 参考
description: 表示 VBA 项目引用的集合。
type: docs
url: /zh/com.aspose.slides/vbareferencecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
```
public class VbaReferenceCollection implements IVbaReferenceCollection
```

表示 VBA 项目引用的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 获取集合中实际包含的元素数量。 |
| [add(IVbaReference value)](#add-com.aspose.slides.IVbaReference-) | 将新引用添加到引用集合。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [iterator()](#iterator--) | 返回一个枚举器，用于遍历集合。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定的数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
### size() {#size--}
```
public final int size()
```


获取集合中实际包含的元素数量。只读 int。

**Returns:**
int
### add(IVbaReference value) {#add-com.aspose.slides.IVbaReference-}
```
public final void add(IVbaReference value)
```


将新引用添加到引用集合。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IVbaReference](../../com.aspose.slides/ivbareference) |  |

### get_Item(int index) {#get-Item-int-}
```
public final IVbaReference get_Item(int index)
```


获取指定索引处的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IVbaReference](../../com.aspose.slides/ivbareference)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iterator()
```


返回一个枚举器，用于遍历集合。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - 可以用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iteratorJava()
```


返回整个集合的 java 迭代器。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - 整个集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


将集合中的所有元素复制到指定的数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 目标数组中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


返回一个值，指示对集合的访问是否同步（线程安全）。只读 boolean。

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


返回同步根。只读 Object。

**Returns:**
java.lang.Object