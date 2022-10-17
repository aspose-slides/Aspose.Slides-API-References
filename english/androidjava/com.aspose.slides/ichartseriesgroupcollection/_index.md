---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides for Android via Java API Reference
description:  Represents the collection of groups of combinable series.
type: docs
weight: 700
url: /androidjava/com.aspose.slides/ichartseriesgroupcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Represents the collection of groups of combinable series.

--------------------

1) Each group of series contains series with combinable types. Groups of combinable series types defined and described with CombinableSeriesTypesGroup enum. Also each group of series contains series witch is plotted whether on primary axes or on secondary axes (not both cases in one group). So, principle of series grouping is a grouping by type groups mentioned above and by primary/secondary plotting type. 2) Group of series contains some series properties which is common for each series in group ("series group properties"). "Series group properties" in ChartSeriesGroup class is read/write. Each of "series group properties" can have a read-only projection in ChartSeries class.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Gets the series group by series. |
| [get_Item(int index)](#get-Item-int-) | Gets the series group by index. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```


Gets the series group by series.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**Returns:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```


Gets the series group by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
