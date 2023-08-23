---
title: ISmartArtNodeCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a collection of SmartArt nodes.
type: docs
url: /com.aspose.slides/ismartartnodecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

Represents a collection of SmartArt nodes.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns node by index. |
| [addNode()](#addNode--) | Add new node or sub node. |
| [removeNode(int index)](#removeNode-int-) | Remove node or sub node by index. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Remove node or sub node. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Add new node in the selected position of nodes collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```


Returns node by index. Read-only [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element. |

**Returns:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```


Add new node or sub node.

**Returns:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Added node
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```


Remove node or sub node by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Zero-based index of node |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```


Remove node or sub node.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Node to remove. |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```


Add new node in the selected position of nodes collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | Zero-base node position. |

**Returns:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Added node
