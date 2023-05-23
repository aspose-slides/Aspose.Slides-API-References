---
title: IActualLayout
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies actual position of a chart element.
type: docs
weight: 626
url: /androidjava/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Specifies actual position of a chart element.
## Methods

| Method | Description |
| --- | --- |
| [getActualX()](#getActualX--) | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. |
| [getActualY()](#getActualY--) | Specifies actual top of the chart element relative to the left top corner of the chart. |
| [getActualWidth()](#getActualWidth--) | Specifies actual width of the chart element. |
| [getActualHeight()](#getActualHeight--) | Specifies actual height of the chart element. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```


Specifies actual x location (left) of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Returns:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```


Specifies actual top of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Returns:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```


Specifies actual width of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Returns:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```


Specifies actual height of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Returns:**
float
