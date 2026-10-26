---
title: ISectionCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个节的集合。
type: docs
url: /zh/com.aspose.slides/isectioncollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

表示一个节的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | 添加从特定幻灯片开始的新节。 |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | 在集合的指定位置添加空节。 |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | 移除该节及其包含的幻灯片。 |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | 移除节。 |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | 将节及其幻灯片从集合中移动到指定位置。 |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | 在集合末尾添加空节。 |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | 返回集合中指定节的索引。 |
| [clear()](#clear--) | 移除集合中的所有节。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
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
public abstract ISection addSection(String name, ISlide startedFromSlide)
```


添加从特定幻灯片开始的新节。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 节的名称 |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | 节的第一张幻灯片 |

**返回值:**
[ISection](../../com.aspose.slides/isection) - 已添加的节。
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```


在集合的指定位置添加空节。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 节的名称 |
| index | int | 新节的索引。 |

**返回值:**
[ISection](../../com.aspose.slides/isection) - 已添加的节。
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```


移除该节及其包含的幻灯片。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要从集合中移除的节。 |
### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```


移除节。该节包含的幻灯片将合并到前一个节。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要从集合中移除的节。 |
### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```


将节及其幻灯片从集合中移动到指定位置。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要移动的节。 |
| index | int | 目标索引。 |
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```


在集合末尾添加空节。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 节的名称 |

**返回值:**
[ISection](../../com.aspose.slides/isection) - 已添加的节。
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```


返回集合中指定节的索引。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要查找的节。 |

**返回值:**
int - 节的索引，如果节不在此集合中则返回 -1。
### clear() {#clear--}
```
public abstract void clear()
```


移除集合中的所有节。