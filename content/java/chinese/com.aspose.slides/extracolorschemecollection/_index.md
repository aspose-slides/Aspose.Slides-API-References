---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides for Java API 参考
description: 表示一个附加配色方案的集合。
type: docs
url: /zh/com.aspose.slides/extracolorschemecollection/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

表示一个附加配色方案的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 返回集合中元素的数量 int。 |
| [get_Item(int index)](#get-Item-int-) | 根据索引返回颜色方案。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合的所有元素复制到指定的数组中。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对 ArrayList 的访问是否已同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回一个可用于同步访问集合的对象。 |
### size() {#size--}
```
public final int size()
```

返回集合中元素的数量 int。只读 int。

**返回：**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

根据索引返回颜色方案。只读 [ExtraColorScheme](../../com.aspose.slides/extracolorscheme)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

返回一个遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将集合的所有元素复制到指定的数组中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the array. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一个值，指示对 ArrayList 的访问是否已同步（线程安全）。只读 boolean。

**返回：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回一个可用于同步访问集合的对象。只读 Object。

返回同步根。只读 Object。

**返回：**
java.lang.Object