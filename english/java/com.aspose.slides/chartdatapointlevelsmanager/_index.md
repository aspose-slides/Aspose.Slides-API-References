---
title: ChartDataPointLevelsManager
second_title: Aspose.Sildes for Java API Reference
description: p
 Container of data point levels.
type: docs
weight: 87
url: /java/com.aspose.slides/chartdatapointlevelsmanager/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
```
public class ChartDataPointLevelsManager extends DomObject<ChartDataPoint> implements IChartDataPointLevelsManager
```

Container of data point levels. Applied for Treeamp and Sunburst series. Data point levels indexing is zero-based.
## Constructors

| Constructor | Description |
| --- | --- |
| [ChartDataPointLevelsManager(ChartDataPoint parent)](#ChartDataPointLevelsManager-com.aspose.slides.ChartDataPoint-) |  |
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Returns IChartDataPointLevel object for defined level. |
| [getCount()](#getCount--) | Returns data point levels count. |
### ChartDataPointLevelsManager(ChartDataPoint parent) {#ChartDataPointLevelsManager-com.aspose.slides.ChartDataPoint-}
```
 ChartDataPointLevelsManager(ChartDataPoint parent)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parent | [ChartDataPoint](../../com.aspose.slides/chartdatapoint) |  |

### get_Item(int level) {#get-Item-int-}
```
public final IChartDataPointLevel get_Item(int level)
```


Returns IChartDataPointLevel object for defined level.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int |  |

**Returns:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public final int getCount()
```


Returns data point levels count.

**Returns:**
int
