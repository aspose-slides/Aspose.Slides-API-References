---
title: ISectionCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a collection of sections.
type: docs
weight: 1007
url: /androidjava/com.aspose.slides/isectioncollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

Represents a collection of sections.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Add new section started form specific slide. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Add empty section to specified position of the collection. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Remove section and slides contained in the section. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Remove section. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Moves section and its slides from the collection to the specified position. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Add empty section to the end of the collection. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Returns an index of the specified section in the collection. |
| [clear()](#clear--) | Removes all sections from the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```


Gets the element at the specified index. Read-only [ISection](../../com.aspose.slides/isection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```


Add new section started form specific slide.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the section |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | First slide of section |

**Returns:**
[ISection](../../com.aspose.slides/isection) - Added section.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```


Add empty section to specified position of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the section |
| index | int | Index of new section. |

**Returns:**
[ISection](../../com.aspose.slides/isection) - Added section.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```


Remove section and slides contained in the section.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | The section to remove from the collection. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```


Remove section. Slides contained in the section will be merged into previous section.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | The section to remove from the collection. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```


Moves section and its slides from the collection to the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Section to move. |
| index | int | Target index. |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```


Add empty section to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the section |

**Returns:**
[ISection](../../com.aspose.slides/isection) - Added section.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```


Returns an index of the specified section in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Section to find. |

**Returns:**
int - Index of a section or -1 if section not from this collection.
### clear() {#clear--}
```
public abstract void clear()
```


Removes all sections from the collection.

