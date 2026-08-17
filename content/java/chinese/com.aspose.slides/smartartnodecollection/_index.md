---
title: SmartArtNodeCollection
second_title: Aspose.Slides Java API 参考
description: 表示 SmartArt 节点的集合。
type: docs
url: /zh/com.aspose.slides/smartartnodecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

表示 SmartArt 节点的集合。

## 方法

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 按索引返回节点 |
| [size()](#size--) | 返回集合中节点的计数，只读 int |
| [addNode()](#addNode--) | 添加新的 SmartArt 节点或子节点。 |
| [removeNode(int index)](#removeNode-int-) | 按索引移除节点或子节点 |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | 移除节点或子节点 |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | 在节点集合的指定位置添加新节点 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将所有元素从集合复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

按索引返回节点

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 元素的零基索引 |

**Returns:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - SmartArt 节点
### size() {#size--}
```
public final int size()
```

返回集合中节点的计数，只读 int

**Returns:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

添加新的 SmartArt 节点或子节点。

**Returns:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 已添加的节点
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

按索引移除节点或子节点

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 节点的零基索引 |
### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

移除节点或子节点

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | 要移除的节点 |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

在节点集合的选定位置添加新节点

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | 零基节点位置 |

**Returns:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 已添加的节点
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

返回遍历集合的枚举器。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

返回整个集合的 java 迭代器。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - 用于整个集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将所有元素从集合复制到指定数组。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 目标数组中的起始索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一个值，指示对集合的访问是否同步（线程安全）。只读 boolean

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object

**Returns:**
java.lang.Object