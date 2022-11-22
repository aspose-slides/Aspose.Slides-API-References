---
title: ISequenceCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents collection of interactive sequences.
type: docs
weight: 1015
url: /androidjava/com.aspose.slides/isequencecollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
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
### getCount() {#getCount--}
```
public abstract int getCount()
```


Returns the number of elements in a collection Read-only int.

**Returns:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```


Add new interactive sequence.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Shape object [IShape](../../com.aspose.slides/ishape) |

**Returns:**
[ISequence](../../com.aspose.slides/isequence) - New sequence [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```


Removes specified sequence from a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Sequence to remove. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes sequence at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of element in the collection int |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all sequences from a collection.

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```


Returns a sequense at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of element. |

**Returns:**
[ISequence](../../com.aspose.slides/isequence) - The [ISequence](../../com.aspose.slides/isequence) object.
