---
title: TabCollection
second_title: Aspose.Slides for Java API Reference
description: Represents a collection of tabs.
type: docs
weight: 547
url: /java/com.aspose.slides/tabcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

Represents a collection of tabs.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Gets the number of elements actually contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [add(double position, int align)](#add-double-int-) | Adds a Tab to the collection. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Adds a Tab to the collection. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether two TabsEx instances are equal. |
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
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```


Gets the element at the specified index. Read-only [Tab](../../com.aspose.slides/tab).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```


Adds a Tab to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**Returns:**
[ITab](../../com.aspose.slides/itab) - Added tab.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```


Adds a Tab to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | The Tab object to be added at the end of the collection. |

**Returns:**
int - The index at which the tab was added.
### clear() {#clear--}
```
public final void clear()
```


Removes all elements from the collection.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes the element at the specified index of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether two TabsEx instances are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The TabsEx to compare with the current TabsEx. |

**Returns:**
boolean - **true** if the specified TabsEx is equal to the current TabsEx; otherwise, **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - An java.util.Iterator for the entire collection.
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
