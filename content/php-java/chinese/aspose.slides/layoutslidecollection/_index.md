---
title: LayoutSlideCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/layoutslidecollection/
---
## LayoutSlideCollection 类

 表示布局幻灯片集合的基类。
 
### getByType {#getByType}

| 名称 | 描述 |
| --- | --- |
| getByType (byte) | 返回指定类型的第一张布局幻灯片。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| type | byte | 要查找的布局幻灯片的类型。 |

 **返回值:**
[LayoutSlide](../layoutslide)


---


### getSyncRoot {#getSyncRoot}

| 名称 | 描述 |
| --- | --- |
| getSyncRoot () | 返回同步根。只读 Object。 |

 **返回值:**
Object


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 通过索引返回布局幻灯片。只读 LayoutSlide。 |

 **返回值:**
[LayoutSlide](../layoutslide)


---


### isSynchronized {#isSynchronized}

| 名称 | 描述 |
| --- | --- |
| isSynchronized () | 返回一个值，指示对集合的访问是否同步（线程安全）。只读 boolean。 |

 **返回值:**
boolean


---


### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回一个枚举器，用于遍历集合。 |

 **返回值:**



---


### iteratorJava {#iteratorJava}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

 **返回值:**



---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([LayoutSlide](../layoutslide)) | 从集合中移除布局。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [LayoutSlide](../layoutslide) | 从集合中移除的布局幻灯片。1) 为避免抛出 PptxEditException，请在此之前检查布局的 HasDependingSlides 属性。2) 您也可以使用 ILayoutSlide#remove 方法来简化代码。 |

 **返回值:**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| PptxEditException | 如果布局在演示文稿中被使用（其 HasDependingSlides 属性为 true），则抛出。 |


---


### removeUnused {#removeUnused}

| 名称 | 描述 |
| --- | --- |
| removeUnused () | 移除未使用的布局幻灯片（HasDependingSlides 为 false 的布局幻灯片）。 |

 **返回值:**
void


---


### size {#size}

| 名称 | 描述 |
| --- | --- |
| size () | 返回集合中布局幻灯片的数量。只读 int。 |

 **返回值:**
int


---