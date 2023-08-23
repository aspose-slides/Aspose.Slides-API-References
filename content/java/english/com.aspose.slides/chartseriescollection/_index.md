---
title: ChartSeriesCollection
second_title: Aspose.Slides for Java API Reference
description: Represents collection of
type: docs
url: /com.aspose.slides/chartseriescollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

Represents collection of [ChartSeries](../../com.aspose.slides/chartseries)
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [size()](#size--) | Returns a number of objects in the collection. |
| [add(int type)](#add-int-) | Creates new chart series and adds it to the collection. |
| [insert(int index, int type)](#insert-int-int-) | Creates new chart series and inserts it into the collection. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Creates new chart series from [ChartDataCell](../../com.aspose.slides/chartdatacell) and adds it to the collection. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Creates new chart series from [ChartCellCollection](../../com.aspose.slides/chartcellcollection) and adds it to the collection. |
| [add(String name, int type)](#add-java.lang.String-int-) | Creates new chart series from value and adds it to the collection. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Searches for the specified [ChartSeries](../../com.aspose.slides/chartseries) and returns the zero-based index of the first occurrence within the entire Collection |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Removes the specified value. |
| [removeAt(int index)](#removeAt-int-) | Removes an ActiveX control stored at specified position from the collection. |
| [clear()](#clear--) | Removes all controls from the collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies the entire collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```


Gets the element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - The element at the specified index.
### size() {#size--}
```
public final int size()
```


Returns a number of objects in the collection. Read-only int.

**Returns:**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```


Creates new chart series and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Type of series |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - New chart series.
### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```


Creates new chart series and inserts it into the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```


Creates new chart series from [ChartDataCell](../../com.aspose.slides/chartdatacell) and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell which contain series name. |
| type | int | Type set type of series

--------------------

If chart series careted from same cell already in collection then method adds nothing and returns it's index. |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Added chart series or series that already is in collection.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```


Creates new chart series from [ChartCellCollection](../../com.aspose.slides/chartcellcollection) and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Cells which contain series name. |
| type | int | Type set type of series

--------------------

If chart series careted from same cell already in collection then method adds nothing and returns it's index. |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Added chart series or series that already is in collection.
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```


Creates new chart series from value and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Series name. |
| type | int | Type set type of series |

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Added chart series.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```


Searches for the specified [ChartSeries](../../com.aspose.slides/chartseries) and returns the zero-based index of the first occurrence within the entire Collection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Chart series value. |

**Returns:**
int - The zero-based index of the first occurrence of value within the entire CollectionBase, if found; otherwise, -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```


Removes the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | The value. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes an ActiveX control stored at specified position from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a control to remove. |

### clear() {#clear--}
```
public final void clear()
```


Removes all controls from the collection.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copies the entire collection to the specified array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array |
| index | int | Index in the target array. |

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
