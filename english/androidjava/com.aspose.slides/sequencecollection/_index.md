---
title: SequenceCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents collection of interactive sequences.
type: docs
weight: 490
url: /androidjava/com.aspose.slides/sequencecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

Represents collection of interactive sequences.
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Returns the number of elements in a collection Read-only int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Add new interactive sequence. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Removes specified sequence from a collection. |
| [removeAt(int index)](#removeAt-int-) | Removes sequence at the specified index. |
| [clear()](#clear--) | Removes all sequences from a collection. |
| [get_Item(int index)](#get-Item-int-) | Returns a sequense at the specified index. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### getCount() {#getCount--}
```
public final int getCount()
```


Returns the number of elements in a collection Read-only int.

**Returns:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```


Add new interactive sequence. Read/write [Sequence](../../com.aspose.slides/sequence).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**Returns:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```


Removes specified sequence from a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Sequence to remove. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes sequence at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a sequence that should be deleted. |

### clear() {#clear--}
```
public final void clear()
```


Removes all sequences from a collection.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```


Returns a sequense at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of element. |

**Returns:**
[ISequence](../../com.aspose.slides/isequence) - The [ISequence](../../com.aspose.slides/isequence) object.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - An java.util.Iterator for the entire collection.
