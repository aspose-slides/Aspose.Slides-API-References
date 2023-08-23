---
title: ColorOperationCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a collection of color transform operations.
type: docs
url: /com.aspose.slides/coloroperationcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Represents a collection of color transform operations.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Returns the number of operations in a collection. |
| [get_Item(int index)](#get-Item-int-) | Returns or sets the operation at the specified index. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Returns or sets the operation at the specified index. |
| [add(int operation, float parameter)](#add-int-float-) | Adds a new operation to the end of collection. |
| [add(int operation)](#add-int-) | Adds a new operation to the end of collection. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Inserts the new operation to a collection. |
| [insert(int position, int operation)](#insert-int-int-) | Inserts the new operation to a collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the color operation from a collection. |
| [clear()](#clear--) | Removes all color operations. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [deepClone()](#deepClone--) | Creates a copy of a ColorOperationCollection collection. |
| [cloneT()](#cloneT--) | Clones current object |
### size() {#size--}
```
public final int size()
```


Returns the number of operations in a collection. Read-only int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```


Returns or sets the operation at the specified index. Read/write [ColorOperation](../../com.aspose.slides/coloroperation).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```


Returns or sets the operation at the specified index. Read/write [ColorOperation](../../com.aspose.slides/coloroperation).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```


Adds a new operation to the end of collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operation | int | Operation type. |
| parameter | float | Operation's parameter. |

**Returns:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Added operation.
### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```


Adds a new operation to the end of collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operation | int | Operation type. |

**Returns:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Added operation.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```


Inserts the new operation to a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | The index at which the operation will be inserted. |
| operation | int | Operation type. |
| parameter | float | Operation's parameter. |

**Returns:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Inserted operation.
### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```


Inserts the new operation to a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | The index at which the operation will be inserted. |
| operation | int | Operation type. |

**Returns:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Inserted operation.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes the color operation from a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a color operation to remove. |

### clear() {#clear--}
```
public final void clear()
```


Removes all color operations.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - An java.util.Iterator for the entire collection.
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
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Creates a copy of a ColorOperationCollection collection.

**Returns:**
java.lang.Object - New [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) collection.
### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```


Clones current object

**Returns:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - Clone
