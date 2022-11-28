---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides for Java API Reference
description: Represents a collection of points that shall be drawn in the second pie or bar on a bar-of-pie or pie-of-pie chart with a custom split.
type: docs
weight: 968
url: /java/com.aspose.slides/ipiesplitcustompointcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Represents a collection of points that shall be drawn in the second pie or bar on a bar-of-pie or pie-of-pie chart with a custom split.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns chart data point by index. |
| [add(int dataPointIndex)](#add-int-) | Adds data point by its index in parent series points collection. |
| [remove(int dataPointIndex)](#remove-int-) | Removes item from collection by it index in parent series points collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```


Returns chart data point by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of data-point. |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Chart data point.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```


Adds data point by its index in parent series points collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataPointIndex | int | Index of data point in parent series points collection. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```


Removes item from collection by it index in parent series points collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataPointIndex | int | Index of data point in parent series points collection.. |

