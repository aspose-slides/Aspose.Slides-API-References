---
title: SectionCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/sectioncollection/
---
## SectionCollection 类

 表示一个章节集合。
 
### addEmptySection {#addEmptySection}

| 名称 | 描述 |
| --- | --- |
| addEmptySection (String, int) | 向集合的指定位置添加空章节。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 章节的名称 |
| index | int | 新章节的索引。 |

**返回:**
[Section](../section)


---


### addSection {#addSection}

| 名称 | 描述 |
| --- | --- |
| addSection (String, [Slide](../slide)) | 从特定幻灯片开始添加幻灯片章节。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 章节的名称 |
| startedFromSlide | [Slide](../slide) | 章节的第一张幻灯片 |

**返回:**
[Section](../section)


---


### appendEmptySection {#appendEmptySection}

| 名称 | 描述 |
| --- | --- |
| appendEmptySection (String) | 向集合末尾添加空章节。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 章节的名称 |

**返回:**
[Section](../section)


---


### clear {#clear}

| 名称 | 描述 |
| --- | --- |
| clear () | 从集合中删除所有章节。 |

**返回:**
void


---


### getSyncRoot {#getSyncRoot}

| 名称 | 描述 |
| --- | --- |
| getSyncRoot () | 返回同步根。只读 Object。 |

**返回:**
Object


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 获取指定索引处的元素。只读 ISection。 |

**返回:**
[Section](../section)


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([Section](../section)) | 返回集合中指定章节的索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| section | [Section](../section) | 要查找的章节。 |

**返回:**
int


---


### isSynchronized {#isSynchronized}

| 名称 | 描述 |
| --- | --- |
| isSynchronized () | 返回一个值，指示对集合的访问是否同步（线程安全）。只读 boolean。 |

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
| iteratorJava () | 返回整个集合的 Java 迭代器。 |

**返回:**



---


### removeSection {#removeSection}

| 名称 | 描述 |
| --- | --- |
| removeSection ([Section](../section)) | 移除章节。章节中包含的幻灯片将合并到前一个章节。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| section | [Section](../section) | 要从集合中移除的章节。 |

**返回:**
void


---


### removeSectionWithSlides {#removeSectionWithSlides}

| 名称 | 描述 |
| --- | --- |
| removeSectionWithSlides ([Section](../section)) | 移除章节及其中包含的幻灯片。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| section | [Section](../section) | 要从集合中移除的章节。 |

**返回:**
void


---


### reorderSectionWithSlides {#reorderSectionWithSlides}

| 名称 | 描述 |
| --- | --- |
| reorderSectionWithSlides ([Section](../section), int) | 将章节及其幻灯片从集合中移动到指定位置。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | [Section](../section) | 目标索引。 |
| section | int | 要移动的章节。 |

**返回:**
void


---


### size {#size}

| 名称 | 描述 |
| --- | --- |
| size () | 获取集合中实际包含的元素数量。只读 int。 |

**返回:**
int


---