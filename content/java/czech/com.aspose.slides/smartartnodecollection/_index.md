---
title: SmartArtNodeCollection
second_title: Aspose.Slides pro Java - referenční příručka API
description: Reprezentuje kolekci uzlů SmartArt.
type: docs
url: /cs/com.aspose.slides/smartartnodecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

Reprezentuje kolekci uzlů SmartArt.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns node by index |
| [size()](#size--) | Returns count of nodes in collection Pouze pro čtení int Pouze pro čtení int . |
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


Returns node by index

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element |

**Vrací:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - The SmartArt node
### size() {#size--}
```
public final int size()
```


Returns count of nodes in collection Pouze pro čtení int Pouze pro čtení int .

**Vrací:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```


Add new smart art node or sub node.

**Vrací:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Added node
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```


Remove node or sub node by index

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Zero-based index of node |

### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```


Remove node or sub node

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Node to remove |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```


Add new node in the selected position of nodes collection

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | Zero-base node position |

**Vrací:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Added node
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```


Returns an enumerator that iterates through the collection.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```


Returns a java iterator for the entire collection.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copies all elements from the collection to the specified array.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the target array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returns a value indicating whether access to the collection is synchronized (thread-safe). Pouze pro čtení boolean .

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returns a synchronization root. Pouze pro čtení Object.

**Vrací:**
java.lang.Object