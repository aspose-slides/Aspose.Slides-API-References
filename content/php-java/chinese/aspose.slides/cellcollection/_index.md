---
title: CellCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/cellcollection/
---
## CellCollection 类

 表示一个单元格集合。
 
### getPresentation {#getPresentation}

| 名称 | 描述 |
| --- | --- |
| getPresentation () | 返回 CellCollection 的父级演示文稿。只读 IPresentation. |

 **返回:**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| 名称 | 描述 |
| --- | --- |
| getSlide () | 返回 CellCollection 的父级幻灯片。只读 IBaseSlide. |

 **返回:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getSyncRoot {#getSyncRoot}

| 名称 | 描述 |
| --- | --- |
| getSyncRoot () | 返回同步根。只读 Object. |

 **返回:**
Object


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 返回指定位置的单元格。只读 Cell。对于合并的单元格，多个索引可能返回同一个 Cell 对象。 |

 **返回:**
[Cell](../cell)


---


### isSynchronized {#isSynchronized}

| 名称 | 描述 |
| --- | --- |
| isSynchronized () | 返回一个值，指示对集合的访问是否同步（线程安全）。只读 boolean. |

 **返回:**
boolean


---


### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回一个遍历集合的枚举器。 |

 **返回:**



---


### iteratorJava {#iteratorJava}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

 **返回:**



---


### size {#size}

| 名称 | 描述 |
| --- | --- |
| size () | 返回集合中单元格的数量。只读 int. |

 **返回:**
int


---