---
title: LayoutSlideCollection
second_title: Aspose.Slides for Android Java API 参考
description: 表示布局幻灯片集合的基类。
type: docs
url: /zh/com.aspose.slides/layoutslidecollection/
---
**继承:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

表示布局幻灯片集合的基类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 返回集合中布局幻灯片的数量。 |
| [get_Item(int index)](#get-Item-int-) | 根据索引返回布局幻灯片。 |
| [getByType(byte type)](#getByType-byte-) | 返回指定类型的第一个布局幻灯片。 |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | 从集合中移除布局。 |
| [removeUnused()](#removeUnused--) | 移除未使用的布局幻灯片（HasDependingSlides 为 false 的布局幻灯片）。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

返回集合中布局幻灯片的数量。只读 int。

**返回：**
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

根据索引返回布局幻灯片。只读 [LayoutSlide](../../com.aspose.slides/layoutslide)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

返回指定类型的第一个布局幻灯片。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | byte | 要查找的布局幻灯片的类型。 |

**返回：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) 具有指定类型，若未找到布局则返回 null。
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

从集合中移除布局。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 要从集合中移除的布局幻灯片。 |

--------------------
1) 为避免抛出 PptxEditException，请在此之前检查布局的 HasDependingSlides 属性。2) 您也可以使用 [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) 方法来简化代码。 |
### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

移除未使用的布局幻灯片（HasDependingSlides 为 false 的布局幻灯片）。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

返回一个遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - 整个集合的 java.util.Iterator。
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
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject