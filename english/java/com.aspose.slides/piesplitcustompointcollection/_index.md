---
title: PieSplitCustomPointCollection
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a collection of points for splitting point in a bar-of-pie or pie-of-pie chart with a custom split.
type: docs
weight: 419
url: /java/com.aspose.slides/piesplitcustompointcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Represents a collection of points for splitting point in a bar-of-pie or pie-of-pie chart with a custom split.
## Constructors

| Constructor | Description |
| --- | --- |
| [PieSplitCustomPointCollection(IChartSeriesGroup parentSeriesGroup)](#PieSplitCustomPointCollection-com.aspose.slides.IChartSeriesGroup-) |  |
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns chart data point for specified index. |
| [add(int dataPointIndex)](#add-int-) | Adds data point by its index in parent series points collection. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Adds data point to collection. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Removes item from collection. |
| [remove(int dataPointIndex)](#remove-int-) | Removes item from collection by it index in parent series points collection. |
| [clear()](#clear--) | Removes all items from the [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index. |
| [size()](#size--) | Returns or sets the count of chart data points. |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### PieSplitCustomPointCollection(IChartSeriesGroup parentSeriesGroup) {#PieSplitCustomPointCollection-com.aspose.slides.IChartSeriesGroup-}
```
 PieSplitCustomPointCollection(IChartSeriesGroup parentSeriesGroup)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentSeriesGroup | [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup) |  |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```


Returns chart data point for specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index. |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Chart data point.
### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```


Adds data point by its index in parent series points collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataPointIndex | int | Index of data point in parent series points collection. |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```


Adds data point to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Data point add to. |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```


Removes item from collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Data point remove to. |

**Returns:**
boolean - true if item is successfully removed; otherwise, false. This method also
  returns false if item was not found in the System.Collections.Generic.List{T}.
### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```


Removes item from collection by it index in parent series points collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataPointIndex | int | Index of data point in parent series points collection. |

### clear() {#clear--}
```
public final void clear()
```


Removes all items from the [IGenericCollection](../../com.aspose.slides/igenericcollection).

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```


Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | The object to locate in the [IGenericCollection](../com.aspose.slides/igenericcollection). |

**Returns:**
boolean - true if item is found in the [IGenericCollection](../com.aspose.slides/igenericcollection); otherwise, false.
### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```


Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.slides.IChartDataPoint[] | The one-dimensional Array that is the destination of the elements copied from [IGenericCollection](../com.aspose.slides/igenericcollection). The Array must have zero-based indexing. |
| arrayIndex | int | The zero-based index in array at which copying begins. |

### size() {#size--}
```
public final int size()
```


Returns or sets the count of chart data points. Read-only int.

**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Gets a value indicating whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only. Read-only boolean.

**Returns:**
boolean - true if the [IGenericCollection](../com.aspose.slides/igenericcollection) is read-only; otherwise, false.
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
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - An java.util.Iterator for the entire collection.
