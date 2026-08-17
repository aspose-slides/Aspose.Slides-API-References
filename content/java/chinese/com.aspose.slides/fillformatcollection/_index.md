---
title: FillFormatCollection
second_title: Aspose.Slides Java API 参考
description: 表示填充样式的集合。
type: docs
url: /zh/com.aspose.slides/fillformatcollection/
---
**继承：**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口：**
[com.aspose.slides.IFillFormatCollection](../../com.aspose.slides/ifillformatcollection)
```java
public final class FillFormatCollection extends DomObject<FormatScheme> implements IFillFormatCollection
```

表示填充样式的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [size()](#size--) | 获取集合中实际包含的元素数量。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
### get_Item(int index) {#get-Item-int-}
```
public final IFillFormat get_Item(int index)
```

获取指定索引处的元素。只读 [IFillFormat](../../com.aspose.slides/ifillformat)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFillFormat> iterator()
```

返回一个遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFillFormat> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - An java.util.Iterator for the entire collection.
### size() {#size--}
```
public final int size()
```

获取集合中实际包含的元素数量。只读 int。

**返回：**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将集合中的所有元素复制到指定数组。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 目标数组中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一个值，指示对集合的访问是否同步（线程安全）。只读 boolean。

**返回：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object。

**返回：**
java.lang.Object