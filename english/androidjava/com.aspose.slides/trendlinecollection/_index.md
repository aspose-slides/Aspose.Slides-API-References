---
title: TrendlineCollection
second_title: Aspose.Slides for Android via Java API Reference
description:  Represents a collection of Trendline
type: docs
weight: 592
url: /androidjava/com.aspose.slides/trendlinecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

Represents a collection of Trendline
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [add(int trendlineType)](#add-int-) | Adds the new Trendline at the end of a collection and return it. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Removes the specified value. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```


Gets the element at the specified index. Read-only [Trendline](../../com.aspose.slides/trendline).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```


Adds the new Trendline at the end of a collection and return it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| trendlineType | int |  |

**Returns:**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```


Removes the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - An java.util.Iterator for the entire collection.
### getCount() {#getCount--}
```
public final int getCount()
```


Gets the number of elements actually contained in the collection. Read-only int.

**Returns:**
int
