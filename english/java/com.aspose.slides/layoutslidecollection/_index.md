---
title: LayoutSlideCollection
second_title: Aspose.Slides for Java API Reference
description: Represents a base class for collection of a layout slides.
type: docs
weight: 261
url: /java/com.aspose.slides/layoutslidecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

Represents a base class for collection of a layout slides.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Returns the number of layout slides in a collection. |
| [get_Item(int index)](#get-Item-int-) | Returns the layout slide by index. |
| [getByType(byte type)](#getByType-byte-) | Returns the first layout slide of specified type. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Removes a layout from the collection. |
| [removeUnused()](#removeUnused--) | Removes unused layout slides (layout slides whose HasDependingSlides is false). |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```


Returns the number of layout slides in a collection. Read-only int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```


Returns the layout slide by index. Read-only [LayoutSlide](../../com.aspose.slides/layoutslide).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```


Returns the first layout slide of specified type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | byte | A type of layout slide to find. |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) with specified type or null if no layouts found.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```


Removes a layout from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | The layout slide to remove from the collection.

--------------------

1) To avoid throwing of the PptxEditException check layout's HasDependingSlides property before. 2) You can use also [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) method to simplify code. |

### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```


Removes unused layout slides (layout slides whose HasDependingSlides is false).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copies all elements from the collection to the specified array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the target array. |

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
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
