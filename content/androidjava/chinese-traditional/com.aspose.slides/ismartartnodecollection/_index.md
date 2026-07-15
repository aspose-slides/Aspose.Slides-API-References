---
title: ISmartArtNodeCollection
second_title: Aspose.Slides 針對 Android 的 Java API 參考
description: 表示 SmartArt 節點的集合。
type: docs
url: /zh-hant/com.aspose.slides/ismartartnodecollection/
---
**所有已實作的介面：**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

表示 SmartArt 節點的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 根據索引傳回節點。 |
| [addNode()](#addNode--) | 新增節點或子節點。 |
| [removeNode(int index)](#removeNode-int-) | 根據索引移除節點或子節點。 |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | 移除節點或子節點。 |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | 在節點集合的選定位置新增節點。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```


根據索引傳回節點。唯讀 [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 元素的零基索引。 |

**傳回：**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```


新增節點或子節點。

**傳回：**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 已新增的節點
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```


根據索引移除節點或子節點。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 節點的零基索引。 |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```


移除節點或子節點。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | 要移除的節點。 |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```


在節點集合的選定位置新增節點。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | int | 節點的零基位置。 |

**傳回：**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 已新增的節點