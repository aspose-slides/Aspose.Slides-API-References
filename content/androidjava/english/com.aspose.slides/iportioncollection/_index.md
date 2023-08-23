---
title: IPortionCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a collection of a portions.
type: docs
url: /com.aspose.slides/iportioncollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Represents a collection of a portions.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Adds a Portion to the end of collection. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Determines the index of a specific portion in collection. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Inserts a Portion into the collection at the specified index. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Removes the first occurrence of a specific object from the [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```


Gets the element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Gets the number of elements actually contained in the collection. Read-only int.

**Returns:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```


Adds a Portion to the end of collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | The Portion to be added to the end of the collection. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```


Determines the index of a specific portion in collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | The portion to locate in the collection. |

**Returns:**
int - The index of item if found in the collection; otherwise, -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```


Inserts a Portion into the collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which Portion should be inserted. |
| value | [IPortion](../../com.aspose.slides/iportion) | The Portion to insert. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all elements from the collection.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```


Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | The object to locate in the [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returns:**
boolean - true if item is found in the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```


Removes the first occurrence of a specific object from the [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | The object to remove from the [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returns:**
boolean - true if item was successfully removed from the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false. This method also returns false if item is not found in the original [IGenericCollection](../../com.aspose.slides/igenericcollection).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the element at the specified index of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

