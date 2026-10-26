---
title: MasterSlideCollection
second_title: Aspose.Sildes for PHP via Java API 参考文档
description: 
type: docs

url: /zh/aspose.slides/masterslidecollection/
---
## MasterSlideCollection 类

 表示一组母版幻灯片。
 
### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([MasterSlide](../masterslide)) | 将指定母版幻灯片的副本添加到集合的末尾。关联的布局幻灯片也将被复制。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| sourceMaster | [MasterSlide](../masterslide) | 要克隆的幻灯片。 |

 **返回：**
[MasterSlide](../masterslide)


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | 返回同步根。只读 Object。 |

 **返回：**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | 获取指定索引处的元素。只读 MasterSlide。 |

 **返回：**
[MasterSlide](../masterslide)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [MasterSlide](../masterslide)) | 在集合的指定位置插入指定母版幻灯片的副本。关联的布局幻灯片也将被复制。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| sourceMaster | [MasterSlide](../masterslide) | 要克隆的幻灯片。 |

 **返回：**
[MasterSlide](../masterslide)


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | 返回一个值，指示对集合的访问是否同步（线程安全）。只读 boolean。 |

 **返回：**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | 返回一个枚举器，用于遍历集合。 |

 **返回：**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

 **返回：**



---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([MasterSlide](../masterslide)) | 从集合中移除指定对象的第一次出现。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| value | [MasterSlide](../masterslide) | 要从集合中移除的母版幻灯片。 |

 **返回：**
void


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | 移除集合中指定索引处的元素。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。为避免抛出 PptxEditException，请在之前检查母版的 HasDependingSlides 属性。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| PptxEditException | 如果要移除的母版在演示文稿中被使用（其 HasDependingSlides 属性为 true），则抛出此异常。 |


---


### removeUnused {#removeUnused}

| Name | Description |
| --- | --- |
| removeUnused (boolean) | 移除未使用的母版幻灯片。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| ignorePreserveField | boolean | 确定即使其 MasterSlide#getPreserve / MasterSlide#setPreserve(boolean) 属性设置为 true，是否仍应移除未使用的母版。 |

 **返回：**
void


---


### size {#size}

| Name | Description |
| --- | --- |
| size () | 获取集合实际包含的元素数量。只读 int。 |

 **返回：**
int


---