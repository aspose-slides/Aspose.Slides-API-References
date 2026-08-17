---
title: ISectionCollection
second_title: Aspose.Slides for Java API 参考
description: 表示一个章节集合。
type: docs
url: /zh/com.aspose.slides/isectioncollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

表示一个章节集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | 添加从特定幻灯片开始的新章节。 |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | 在集合的指定位置添加空章节。 |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | 移除章节及其包含的幻灯片。 |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | 移除章节。 |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | 将章节及其幻灯片从集合移动到指定位置。 |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | 在集合末尾添加空章节。 |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | 返回集合中指定章节的索引。 |
| [clear()](#clear--) | 移除集合中的所有章节。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```


获取指定索引处的元素。只读 [ISection](../../com.aspose.slides/isection)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```


添加从特定幻灯片开始的新章节。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 章节的名称 |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | 章节的第一张幻灯片 |

**返回值：**
[ISection](../../com.aspose.slides/isection) - 已添加的章节。
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```


在集合的指定位置添加空章节。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 章节的名称 |
| index | int | 新章节的索引。 |

**返回值：**
[ISection](../../com.aspose.slides/isection) - 已添加的章节。
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```


移除章节及其包含的幻灯片。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要从集合中移除的章节。 |
### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```


移除章节。章节中包含的幻灯片将合并到前一个章节。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要从集合中移除的章节。 |
### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```


将章节及其幻灯片从集合移动到指定位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要移动的章节。 |
| index | int | 目标索引。 |
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```


在集合末尾添加空章节。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 章节的名称 |

**返回值：**
[ISection](../../com.aspose.slides/isection) - 已添加的章节。
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```


返回集合中指定章节的索引。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要查找的章节。 |

**返回值：**
int - 章节的索引，如果章节不在此集合中则返回 -1。
### clear() {#clear--}
```
public abstract void clear()
```


移除集合中的所有章节。