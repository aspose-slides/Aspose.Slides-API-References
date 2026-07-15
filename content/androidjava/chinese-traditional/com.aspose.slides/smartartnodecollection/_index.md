---
title: SmartArtNodeCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示一個 SmartArt 節點的集合。
type: docs
url: /zh-hant/com.aspose.slides/smartartnodecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

表示一個 SmartArt 節點的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns node by index |
| [size()](#size--) | Returns count of nodes in collection Read-only  int  Read-only  int . |
| [addNode()](#addNode--) | Add new smart art node or sub node. |
| [removeNode(int index)](#removeNode-int-) | Remove node or sub node by index |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Remove node or sub node |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Add new node in the selected position of nodes collection |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

返回指定索引的節點

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | The zero-based index of the element |

**Returns:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - SmartArt 節點
### size() {#size--}
```
public final int size()
```

唯讀  int  唯讀  int .

**Returns:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

新增 smart art 節點或子節點。

**Returns:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 已新增的節點
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

依索引移除節點或子節點

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | Zero-based index of node |

### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

移除節點或子節點

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Node to remove |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

在節點集合中於指定位置新增節點

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | int | Zero-base node position |

**Returns:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 已新增的節點
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

返回可遍歷集合的列舉器。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

返回整個集合的 java 迭代器。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the target array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

唯讀  boolean .

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

唯讀 Object.

**Returns:**
java.lang.Object