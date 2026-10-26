---
title: SectionCollection
second_title: Aspose.Slides for Java API 参考
description: 表示一个章节集合。
type: docs
url: /zh/com.aspose.slides/sectioncollection/
---
**继承:**  
java.lang.Object, com.aspose.slides.DomObject

**已实现的接口:**  
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)  
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

表示一个章节集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | 添加从特定幻灯片开始的章节。 |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | 在集合末尾添加空章节。 |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | 在集合的指定位置添加空章节。 |
| [size()](#size--) | 获取集合实际包含的元素数量。 |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | 返回集合中指定章节的索引。 |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | 删除章节及其包含的幻灯片。 |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | 删除章节。 |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | 将章节及其幻灯片从集合移动到指定位置。 |
| [clear()](#clear--) | 删除集合中的所有章节。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将整个集合复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个指示集合访问是否同步（线程安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

获取指定索引处的元素。只读 [ISection](../../com.aspose.slides/isection)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

添加从特定幻灯片开始的章节。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 章节名称 |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | 章节的第一张幻灯片 |

**返回值:**
[ISection](../../com.aspose.slides/isection) - 已添加的章节。
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

在集合末尾添加空章节。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 章节名称 |

**返回值:**
[ISection](../../com.aspose.slides/isection) - 已添加的章节。
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

在集合的指定位置添加空章节。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 章节名称 |
| index | int | 新章节的索引。 |

**返回值:**
[ISection](../../com.aspose.slides/isection) - 已添加的章节。
### size() {#size--}
```
public final int size()
```

获取集合实际包含的元素数量。只读 int。

**返回值:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

返回集合中指定章节的索引。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要查找的章节。 |

**返回值:**
int - 章节的索引，若章节不在此集合中则为 -1。
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

删除章节及其包含的幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要从集合中删除的章节。 |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

删除章节。章节中包含的幻灯片将合并到前一个章节。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要从集合中删除的章节。 |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

将章节及其幻灯片从集合移动到指定位置。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要移动的章节。 |
| index | int | 目标索引。 |

### clear() {#clear--}
```
public final void clear()
```

删除集合中的所有章节。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将整个集合复制到指定数组。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组 |
| index | int | 目标数组中的索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一个指示集合访问是否同步（线程安全）的值。只读 boolean。

**返回值:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object。

**返回值:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

返回一个遍历集合的枚举器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - 用于整个集合的 java.util.Iterator。