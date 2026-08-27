---
title: SmartArtNodeCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/smartartnodecollection/
---
## SmartArtNodeCollection 类

 表示一个 SmartArt 节点的集合。

### addNode {#addNode}

| 名称 | 描述 |
| --- | --- |
| addNode () | 添加新的 smart art 节点或子节点。 |

 **返回值：**
[SmartArtNode](../smartartnode)


---


### addNodeByPosition {#addNodeByPosition}

| 名称 | 描述 |
| --- | --- |
| addNodeByPosition (int) | 在节点集合的指定位置添加新节点 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| position | int | 零基节点位置 |

 **返回值：**
[SmartArtNode](../smartartnode)

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentOutOfRangeException | position 小于 0 |


---


### getSyncRoot {#getSyncRoot}

| 名称 | 描述 |
| --- | --- |
| getSyncRoot () | 返回同步根。只读对象。 |

 **返回值：**
Object


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 根据索引返回节点 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 元素的零基索引 |

 **返回值：**
[SmartArtNode](../smartartnode)


---


### isSynchronized {#isSynchronized}

| 名称 | 描述 |
| --- | --- |
| isSynchronized () | 返回一个值，指示对集合的访问是否同步（线程安全）。只读布尔值。 |

 **返回值：**
boolean


---


### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回一个枚举器，用于遍历集合。 |

 **返回值：**



---


### iteratorJava {#iteratorJava}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

 **返回值：**



---


### removeNode {#removeNode}

| 名称 | 描述 |
| --- | --- |
| removeNode (int) | 按索引删除节点或子节点 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 节点的零基索引 |

 **返回值：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentOutOfRangeException | index 小于 0。-or- index 等于或大于同级节点数 |


---


### removeNode {#removeNode}

| 名称 | 描述 |
| --- | --- |
| removeNode ([SmartArtNode](../smartartnode)) | 删除节点或子节点 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| node | [SmartArtNode](../smartartnode) | 要删除的节点 |

 **返回值：**
void


---


### size {#size}

| 名称 | 描述 |
| --- | --- |
| size () | 返回集合中节点的计数。只读 int。 |

 **返回值：**
int


---