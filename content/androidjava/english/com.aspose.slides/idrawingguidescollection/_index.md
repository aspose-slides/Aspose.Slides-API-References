---
title: IDrawingGuidesCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a collection of the adjustable drawing guides.
type: docs
url: /com.aspose.slides/idrawingguidescollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Represents a collection of the adjustable drawing guides.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the drawing guide by index. |
| [add(byte orientation, float position)](#add-byte-float-) | Adds the drawing guide at the end of the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the drawing guide at the specified index. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [getCount()](#getCount--) | Gets the number of all elements in the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```


Returns the drawing guide by index. Read-only [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```


Adds the drawing guide at the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| orientation | byte | Orientation of the drawing guide. |
| position | float | Position of the the drawing guide in points. |

**Returns:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the drawing guide at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of the drawing guide that should be deleted. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all elements from the collection.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Gets the number of all elements in the collection. Read-only int.

**Returns:**
int
