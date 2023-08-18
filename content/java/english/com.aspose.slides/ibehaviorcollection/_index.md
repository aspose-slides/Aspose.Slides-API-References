---
title: IBehaviorCollection
second_title: Aspose.Slides for Java API Reference
description: Represents collection of behavior effects.
type: docs
url: /com.aspose.slides/ibehaviorcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

Represents collection of behavior effects.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns a behavior at the specified index. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Returns a behavior at the specified index. |
| [getCount()](#getCount--) | Returns the number of behaviors in a collection. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Add new behavior to a collection. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Determines the index of a specific item in the List. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Inserts new behavior to a collection at the specified index. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Removes specified behavior from a collection. |
| [removeAt(int index)](#removeAt-int-) | Removes behavior from a collection at the specified index. |
| [clear()](#clear--) | Removes all behaviors from a collection. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
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
public abstract void set_Item(int index, IBehavior value)
```


Returns a behavior at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a behavior to return. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```


Returns the number of behaviors in a collection. Read-only int.

**Returns:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```


Add new behavior to a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Behavior to add. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
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
public abstract void insert(int index, IBehavior item)
```


Inserts new behavior to a collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index where new behavior should be inserted. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Behavior to insert. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```


Removes specified behavior from a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Behavior to remove. |

**Returns:**
boolean - True if a behavior removed successfully boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes behavior from a collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a behavior to remove. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all behaviors from a collection.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```


Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | The object to locate in the [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returns:**
boolean - true if item is found in the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false.
