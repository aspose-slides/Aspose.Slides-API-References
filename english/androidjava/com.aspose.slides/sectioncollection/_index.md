---
title: SectionCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a collection of sections.
type: docs
weight: 482
url: /androidjava/com.aspose.slides/sectioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

Represents a collection of sections.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Add slides section started form specific slide. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Add empty section to the end of the collection. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Add empty section to specified position of the collection. |
| [size()](#size--) | Gets the number of elements actually contained in the collection. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Returns an index of the specified section in the collection. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Remove section and slides contained in the section. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Remove section. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Moves section and its slides from the collection to the specified position. |
| [clear()](#clear--) | Removes all sections from the collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies the entire collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
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
public final ISection addSection(String name, ISlide startedFromSlide)
```


Add slides section started form specific slide.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the section |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | First slide of section |

**Returns:**
[ISection](../../com.aspose.slides/isection) - Added section.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```


Add empty section to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the section |

**Returns:**
[ISection](../../com.aspose.slides/isection) - Added section.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```


Add empty section to specified position of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the section |
| index | int | Index of new section. |

**Returns:**
[ISection](../../com.aspose.slides/isection) - Added section.
### size() {#size--}
```
public final int size()
```


Gets the number of elements actually contained in the collection. Read-only int.

**Returns:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```


Returns an index of the specified section in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Section to find. |

**Returns:**
int - Index of a section or -1 if section not from this collection.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```


Remove section and slides contained in the section.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | The section to remove from the collection. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```


Remove section. Slides contained in the section will be merged into previous section.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | The section to remove from the collection. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```


Moves section and its slides from the collection to the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Section to move. |
| index | int | Target index. |

### clear() {#clear--}
```
public final void clear()
```


Removes all sections from the collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copies the entire collection to the specified array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array |
| index | int | Index in the target array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returns a synchronization root. Read-only Object.

**Returns:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - An java.util.Iterator for the entire collection.
