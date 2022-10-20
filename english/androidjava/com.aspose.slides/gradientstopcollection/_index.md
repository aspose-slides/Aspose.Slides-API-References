---
title: GradientStopCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represnts a collection of gradient stops.
type: docs
weight: 228
url: /androidjava/com.aspose.slides/gradientstopcollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

Represnts a collection of gradient stops.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Returns the number of gradient stops in a collection. |
| [get_Item(int index)](#get-Item-int-) | Returns the gradient stop by index. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Creates the new gradient stop and adds it to the end of collection. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Creates the new gradient stop and adds it to the end of collection. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Creates the new gradient stop and adds it to the end of collection. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Creates the new gradient stop and inserts it at the specified index to the collection. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Creates the new gradient stop and inserts it at the specified index to the collection. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Creates the new gradient stop and inserts it at the specified index to the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes a gradient stop at the specified index. |
| [clear()](#clear--) | Removes all gradient stops from a collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
### size() {#size--}
```
public final int size()
```


Returns the number of gradient stops in a collection. Read-only  int .

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```


Returns the gradient stop by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```


Creates the new gradient stop and adds it to the end of collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | float | Position of the new gradient stop. |
| color | java.lang.Integer | Color of the new radient stop. |

**Returns:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index of the new gradient stop in the collection.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```


Creates the new gradient stop and adds it to the end of collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | float | Position of the new gradient stop. |
| presetColor | int | Color of the new radient stop. |

**Returns:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index of the new gradient stop in the collection.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```


Creates the new gradient stop and adds it to the end of collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | float | Position of the new gradient stop. |
| schemeColor | int | Color of the new radient stop. |

**Returns:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index of the new gradient stop in the collection.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```


Creates the new gradient stop and inserts it at the specified index to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index in the collection where new gradient stop will be inserted. |
| position | float | Position of the new gradient stop. |
| color | java.lang.Integer | Color of the new radient stop. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```


Creates the new gradient stop and inserts it at the specified index to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index in the collection where new gradient stop will be inserted. |
| position | float | Position of the new gradient stop. |
| presetColor | int | Color of the new radient stop. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```


Creates the new gradient stop and inserts it at the specified index to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index in the collection where new gradient stop will be inserted. |
| position | float | Position of the new gradient stop. |
| schemeColor | int | Color of the new radient stop. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes a gradient stop at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a gradient stop that should be deleted. |

### clear() {#clear--}
```
public final void clear()
```


Removes all gradient stops from a collection.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - An java.util.Iterator for the entire collection.
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


Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only  boolean .

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returns a synchronization root. Read-only Object.

**Returns:**
java.lang.Object
