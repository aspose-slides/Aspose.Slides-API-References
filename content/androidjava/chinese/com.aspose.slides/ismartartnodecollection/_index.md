---
title: ISmartArtNodeCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 SmartArt 节点的集合。
type: docs
url: /zh/com.aspose.slides/ismartartnodecollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

表示 SmartArt 节点的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引的节点。 |
| [addNode()](#addNode--) | 添加新节点或子节点。 |
| [removeNode(int index)](#removeNode-int-) | 按索引删除节点或子节点。 |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | 删除节点或子节点。 |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | 在节点集合的选定位置添加新节点。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```


返回指定索引的节点。只读 [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 元素的零基索引。 |

**返回：**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```


添加新节点或子节点。

**返回：**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 已添加的节点
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```


按索引删除节点或子节点。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 节点的零基索引 |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```


删除节点或子节点。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | 要删除的节点。 |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```


在节点集合的选定位置添加新节点。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | int | 节点的零基位置。 |

**返回：**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 已添加的节点