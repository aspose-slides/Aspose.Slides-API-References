---
title: SmartArtNodeCollection
second_title: Aspose.Slides for Java API 參考
description: 表示 SmartArt 節點的集合。
type: docs
url: /zh-hant/com.aspose.slides/smartartnodecollection/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

表示 SmartArt 節點的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 傳回索引處的節點 |
| [size()](#size--) | 傳回集合中節點的計數 唯讀  int  唯讀  int . |
| [addNode()](#addNode--) | 新增 smart art 節點或子節點。 |
| [removeNode(int index)](#removeNode-int-) | 依索引移除節點或子節點 |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | 移除節點或子節點 |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | 在節點集合中於選定位置新增節點 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示集合存取是否已同步（執行緒安全）的值 唯讀  boolean . |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。唯讀 Object. |

### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

傳回索引處的節點

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 元素的零基索引 |

**傳回值：**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - SmartArt 節點

### size() {#size--}
```
public final int size()
```

傳回集合中節點的計數 唯讀  int  唯讀  int .

**傳回值：**
int

### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

新增 smart art 節點或子節點。

**傳回值：**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 已新增的節點

### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

依索引移除節點或子節點

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 節點的零基索引 |

### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

移除節點或子節點

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | 要移除的節點 |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

在節點集合中於選定位置新增節點

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| position | int | 節點的零基位置 |

**傳回值：**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 已新增的節點

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

傳回可遍歷集合的列舉器。

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - 可用於遍歷集合的 IGenericEnumerator

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - 整個集合的 java.util.Iterator

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中所有元素複製到指定的陣列。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回指示集合存取是否已同步（執行緒安全）的值 唯讀  boolean .

**傳回值：**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object.

**傳回值：**
java.lang.Object