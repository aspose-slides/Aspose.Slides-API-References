---
title: DrawingGuidesCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示可调绘图指南的集合。
type: docs
url: /zh/com.aspose.slides/drawingguidescollection/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

表示可调绘图指南的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引的绘图指南。 |
| [add(byte orientation, float position)](#add-byte-float-) | 在集合末尾添加绘图指南。 |
| [removeAt(int index)](#removeAt-int-) | 删除指定索引处的绘图指南。 |
| [clear()](#clear--) | 删除集合中的所有元素。 |
| [iterator()](#iterator--) | 返回用于遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [getCount()](#getCount--) | 返回集合中元素的数量。 |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | 将集合中的所有元素复制到指定的数组。 |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```

返回指定索引的绘图指南。只读 [IDrawingGuide](../../com.aspose.slides/idrawingguide)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```

在集合末尾添加绘图指南。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| orientation | byte | 绘图指南的方向。 |
| position | float | 绘图指南的位置（以点为单位）。 |

**返回:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

删除指定索引处的绘图指南。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要删除的绘图指南的索引。 |

### clear() {#clear--}
```
public final void clear()
```

删除集合中的所有元素。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```

返回用于遍历集合的枚举器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - 整个集合的 java.util.Iterator。
### getCount() {#getCount--}
```
public final int getCount()
```

返回集合中元素的数量。只读 int。

**返回:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```

将集合中的所有元素复制到指定的数组。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | 目标数组。 |
| index | int | 目标数组中的起始索引。 |