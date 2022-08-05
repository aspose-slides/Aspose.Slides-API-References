---
title: BehaviorCollection
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents collection of behavior effects.
type: docs
weight: 50
url: /java/com.aspose.slides/behaviorcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

Represents collection of behavior effects.
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Returns the number of behaviors in a collection. |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Add new behavior to a collection. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Determines the index of a specific item in the List. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Inserts new behavior to a collection at the specified index. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Removes specified behavior from a collection. |
| [removeAt(int index)](#removeAt-int-) | Removes behavior from a collection at the specified index. |
| [clear()](#clear--) | Removes all behaviors from a collection. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value. |
| [get_Item(int index)](#get-Item-int-) | Returns a behavior at the specified index. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Sets a behavior at the specified index. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### getCount() {#getCount--}
```
public final int getCount()
```


Returns the number of behaviors in a collection. Read-only int.

**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Gets a value indicating whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only. Read-only boolean.

**Returns:**
boolean - true if the [IGenericCollection](../com.aspose.slides/igenericcollection) is read-only; otherwise, false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```


Add new behavior to a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Behavior to add. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```


Determines the index of a specific item in the List.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | The object to locate in the List. |

**Returns:**
int - The index of item if found in the list; otherwise, -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```


Inserts new behavior to a collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index where new behavior should be inserted. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Behavior to insert. |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```


Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.slides.IBehavior[] | The one-dimensional Array that is the destination of the elements copied from [IGenericCollection](../com.aspose.slides/igenericcollection). The Array must have zero-based indexing. |
| arrayIndex | int | The zero-based index in array at which copying begins. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```


Removes specified behavior from a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Behavior to remove. |

**Returns:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes behavior from a collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a behavior to remove. |

### clear() {#clear--}
```
public final void clear()
```


Removes all behaviors from a collection.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```


Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | The object to locate in the [IGenericCollection](../com.aspose.slides/igenericcollection). |

**Returns:**
boolean - true if item is found in the [IGenericCollection](../com.aspose.slides/igenericcollection); otherwise, false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```


Returns a behavior at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a behavior to return. |

**Returns:**
[IBehavior](../../com.aspose.slides/ibehavior) - Animation behavior.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```


Sets a behavior at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a behavior to return. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - An java.util.Iterator for the entire collection.
