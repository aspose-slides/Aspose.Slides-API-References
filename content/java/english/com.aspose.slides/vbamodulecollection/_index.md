---
title: VbaModuleCollection
second_title: Aspose.Slides for Java API Reference
description: Represents a collection of a VBA Project modules.
type: docs
weight: 600
url: /com.aspose.slides/vbamodulecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

Represents a collection of a VBA Project modules.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Gets the number of elements actually contained in the collection. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Removes the first occurrence of a specific object from the collection. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Adds a new empty module to the VBA Project. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
### size() {#size--}
```
public final int size()
```


Gets the number of elements actually contained in the collection. Read-only int.

**Returns:**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```


Removes the first occurrence of a specific object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | The module to remove from the collection. |

### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```


Adds a new empty module to the VBA Project.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the module |

**Returns:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Added module.
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```


Gets the element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - An java.util.Iterator for the entire collection.
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
