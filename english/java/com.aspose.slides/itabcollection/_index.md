---
title: ITabCollection
second_title: Aspose.Slides for Java API Reference
description:  Represents a collection of tabs.
type: docs
weight: 1054
url: /java/com.aspose.slides/itabcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Represents a collection of tabs.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [add(double position, int align)](#add-double-int-) | Adds a Tab to the collection. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Adds a Tab to the collection. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```


Gets the element at the specified index. Read-only [ITab](../../com.aspose.slides/itab).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```


Adds a Tab to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | double | Tab position. |
| align | int | Tab alignment. |

**Returns:**
[ITab](../../com.aspose.slides/itab) - Added tab.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
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
public abstract void clear()
```


Removes all elements from the collection.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the element at the specified index of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

