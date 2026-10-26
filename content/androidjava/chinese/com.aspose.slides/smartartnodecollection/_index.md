---
title: SmartArtNodeCollection
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示一个 SmartArt 节点的集合。
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

表示一个 SmartArt 节点的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 按索引返回节点 |
| [size()](#size--) | 返回集合中节点的计数 只读 int 只读 int 。 |
| [addNode()](#addNode--) | 添加新的 SmartArt 节点或子节点。 |
| [removeNode(int index)](#removeNode-int-) | 按索引删除节点或子节点 |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | 删除节点或子节点 |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | 在节点集合的选定位置添加新节点 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回指示对集合的访问是否同步（线程安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |

### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

按索引返回节点

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 元素的零基索引 |

**返回:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - SmartArt 节点

### size() {#size--}
```
public final int size()
```

返回集合中节点的计数 只读 int 只读 int 。

**返回:**
int

### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

添加新的 SmartArt 节点或子节点。

**返回:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 已添加的节点

### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

按索引删除节点或子节点

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 节点的零基索引 |

### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

删除节点或子节点

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | 要删除的节点 |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

在节点集合的选定位置添加新节点

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | int | 节点的零基位置 |

**返回:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 已添加的节点

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

返回遍历集合的枚举器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - 用于整个集合的 java.util.Iterator。

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

返回指示对集合的访问是否同步（线程安全）的值。只读 boolean 。

**返回:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object。

**返回:**
java.lang.Object