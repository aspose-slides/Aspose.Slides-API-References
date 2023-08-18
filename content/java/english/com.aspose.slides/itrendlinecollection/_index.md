---
title: ITrendlineCollection
second_title: Aspose.Slides for Java API Reference
description: Represents a collection of TrendlineEx
type: docs
url: /com.aspose.slides/itrendlinecollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

Represents a collection of TrendlineEx
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
| [add(int trendlineType)](#add-int-) | Adds the new Trendline at the end of a collection and return it. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Removes the specified value. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```


Gets the element at the specified index. Read-only [ITrendline](../../com.aspose.slides/itrendline).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Gets the number of elements actually contained in the collection. Read-only int.

**Returns:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```


Adds the new Trendline at the end of a collection and return it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| trendlineType | int | Trendline type [TrendlineType](../../com.aspose.slides/trendlinetype) |

**Returns:**
[ITrendline](../../com.aspose.slides/itrendline) - New Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```


Removes the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline to remove [ITrendline](../../com.aspose.slides/itrendline) |

