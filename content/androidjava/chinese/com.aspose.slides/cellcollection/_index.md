---
title: CellCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个单元格集合。
type: docs
url: /zh/com.aspose.slides/cellcollection/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject  
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

表示一个单元格集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | 返回集合中单元格的数量。 |
| [get_Item(int index)](#get-Item-int-) | 根据其位置返回单元格。 |
| [iterator()](#iterator--) | 返回一个枚举器，用于遍历集合。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [getSlide()](#getSlide--) | 返回 CellCollection 的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回 CellCollection 的父演示文稿。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定的数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回:**  
com.aspose.slides.IDOMObject

### size() {#size--}
```
public final int size()
```

返回集合中单元格的数量。只读 int。

**返回:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```

根据其位置返回单元格。只读 [Cell](../../com.aspose.slides/cell)。

--------------------

如果单元格已合并，一个 Cell 对象可能对应多个索引。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回:**  
[ICell](../../com.aspose.slides/icell)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```

返回一个枚举器，用于遍历集合。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - 整个集合的 java.util.Iterator。

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回 CellCollection 的父幻灯片。只读 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**返回:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 CellCollection 的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回:**  
[IPresentation](../../com.aspose.slides/ipresentation)

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

返回一个值，指示对集合的访问是否同步（线程安全）。只读 boolean。

**返回:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object。

**返回:**  
java.lang.Object